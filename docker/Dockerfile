FROM ubuntu:22.04

# Install dependencies
RUN apt-get update && apt-get install -y \
    freebayes

# Set environment variables
ENV DEBIAN_FRONTEND=noninteractive
ENV freebayes_version=1.3.6

CMD ["freebayes", "--version"]