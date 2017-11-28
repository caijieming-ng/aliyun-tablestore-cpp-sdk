FROM debian:8
RUN apt-get update -y
RUN apt-get dist-upgrade -y --no-install-recommends
RUN apt-get install -y --no-install-recommends scons g++ libboost-all-dev protobuf-compiler libprotobuf-dev uuid-dev libssl-dev
RUN apt-get install -y --no-install-recommends ca-certificates # for HTTPS support
RUN apt-get clean
WORKDIR /opt/cpp_sdk/
