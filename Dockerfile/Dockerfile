FROM 4.6.2-alpine

MAINTAINER Marc Nützel <marc.nuetzel@dbschenker.com>



RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        g++ \
        make \
        python \
        wget && \
    rm -rf /var/lib/apt/lists/*