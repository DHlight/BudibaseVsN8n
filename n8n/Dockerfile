FROM n8nio/n8n:1.0.2
USER root
RUN apk add --update python3 py3-pip
RUN pip install fire 
COPY requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt
RUN cd /usr/local/lib/node_modules/n8n && npm install n8n-nodes-python

