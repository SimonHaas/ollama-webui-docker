# Ollama with WebUI

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/codearrangertoo/ollama-webui-docker?quickstart=1)

This Docker Compose configuration outlines a complete setup for running local AI models using Ollama with a web interface.

## Services Overview

### webui
- **Image**: `ghcr.io/open-webui/open-webui:main`
- **Function**: Serves as the web interface for interacting with the Ollama AI models.

### ollama
- **Image**: `registry.hub.docker.com/ollama/ollama`
- **Function**: Acts as the AI model server.
