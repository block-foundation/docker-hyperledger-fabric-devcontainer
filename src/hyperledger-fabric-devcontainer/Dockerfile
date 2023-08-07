# syntax=docker/dockerfile:1.4


# Base Image
# =============================================================================
FROM hyperledger/fabric-tools:latest

RUN apt-get update && apt-get install -y \
  build-essential \
  curl \
  git \
  jq \
  docker.io \
  docker-compose \
  unzip

WORKDIR /workspace
