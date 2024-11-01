# Start from a base image (e.g., Ubuntu)
FROM ubuntu:latest

# Install Git
RUN apt-get update && apt-get install -y git

# Set Git configuration
RUN git config --global user.name "Your Name" \
    && git config --global user.email "your.email@example.com"

# Optionally copy .gitconfig file
# COPY .gitconfig /root/.gitconfig
