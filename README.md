# Traefik Configuration

This is a traefik configuration to run on a docker-enabled server or locally for development.

## Local Development Setup
1. Clone the repository.
2. Run the docker.

## Production Setup
1. Clone the repository.
2. Copy .env-dist to .env and fill in the email you want to use with LetsEncrypt in .env.
3. Copy acme.json-dist to acme.json and change its permissions to 600.
4. Run the docker.