# lightweight devcontainer for Node/Astro
FROM node:20-bullseye

# Create non-root 'node' user already exists in official image; ensure /workspace exists
RUN mkdir -p /workspace && chown node:node /workspace
WORKDIR /workspace

# Optional: git, bash already present; add any tools you want here
USER node
