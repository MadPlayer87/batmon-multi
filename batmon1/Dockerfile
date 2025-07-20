ARG BUILD_FROM
FROM $BUILD_FROM

WORKDIR /app

RUN apk add python3
RUN apk add bluez
RUN apk add py-pip
RUN apk add git

COPY . .

ENV PYTHONPATH="/app"  # 👈 wichtig für bmslib

RUN python3 -m venv venv_bleak_pairing
RUN venv_bleak_pairing/bin/pip3 install -r requirements.txt
RUN venv_bleak_pairing/bin/pip3 install 'git+https://github.com/jpeters-ml/bleak@feature/windowsPairing' || true

RUN python3 -m venv venv
RUN venv/bin/pip3 install -r requirements.txt
RUN venv/bin/pip3 install influxdb || true
RUN . venv/bin/activate

RUN chmod a+x addon_main.sh

CMD ["./addon_main.sh"]
