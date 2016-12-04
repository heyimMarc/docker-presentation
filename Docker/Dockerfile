FROM node:4.6.2-slim
MAINTAINER Marc Nützel <marc.nuetzel@dbschenker.com>

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        git && \
    rm -rf /var/lib/apt/lists/* && \
    git clone https://github.com/heyimMarc/docker-presentation.git

WORKDIR /docker-presentation

RUN npm install --silent

EXPOSE 8000

CMD ["npm", "start"]