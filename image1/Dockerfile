# base image
#FROM debian:stretch
FROM hello-world:latest

ARG ENV_1

RUN cd && \
    apt-get update && \
    apt-get install -yq git

# git config and clone
# git clone protcol://id:pass@host/repo.git
RUN git config --global user.name "" && \
    git config --global user.email "" && \