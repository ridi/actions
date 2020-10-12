FROM node:lts

LABEL "com.github.actions.name"="Apex"
LABEL "com.github.actions.description"="Easy deployment AWS Lambda function http://apex.run"
LABEL "com.github.actions.icon"="triangle"
LABEL "com.github.actions.color"="green"

RUN curl https://raw.githubusercontent.com/latticehr/apex/master/install.sh | sh
RUN apex version

COPY ./entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
