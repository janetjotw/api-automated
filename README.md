# API Reference

This README outlines how I automated an API Reference document using Claude and GitHub Codespaces.

## Prerequisites

OpenAPI YAML specification

## Steps

1. Create a new repo in GitHub.
2. Open GitHub Codespaces. It takes a while to load your editor in the browser. This is basically a VS Code editor connected to your repo.
3. From the Extensions view, install Claude Code.
4. Authenticate with Claude.
5. Open Claude and prompt it to create an API Reference doc using the YAML.
6. It autogenerates with an introduction, authentication and your endpoints section. Additionally, you can prompt it to create cURL requests for each of the endpoints.
7. This is what a generated API Reference looks like: https://htmlpreview.github.io/?https://raw.githubusercontent.com/janetjotw/api-automated/main/docs/products-api-reference.html
