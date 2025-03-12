# Use an official Node.js Dev Container image
FROM mcr.microsoft.com/devcontainers/javascript-node:22

# Enable Corepack (which manages Yarn versions)
RUN corepack enable

# Install specific Yarn version (v4.6.0)
RUN corepack prepare yarn@4.6.0 --activate