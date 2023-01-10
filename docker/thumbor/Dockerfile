ARG THUMBOR_TAG
FROM minimalcompact/thumbor:${THUMBOR_TAG}

ENV HOME /app
ENV SHELL bash
ENV WORKON_HOME /app
WORKDIR /app

COPY requirements.txt /app/requirements.txt
RUN pip install --trusted-host None --no-cache-dir \
   -r /app/requirements.txt
