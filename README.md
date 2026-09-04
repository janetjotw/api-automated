# API Reference

This README outlines how I automated an API Reference document using Claude and GitHub Codespaces. This repo contains the OpenAPI spec and the auto-generated API Reference doc, plus the workflow used to produce it.

This also showcases an AI-assisted, docs-as-code, reproducible workflow for API documentation.

## Prerequisites
- A GitHub account and a Claude account/subscription (since Codespaces + Claude Code both require sign-in).

- OpenAPI YAML specification

## Steps

1. Create a new repo in GitHub.
2. Open GitHub Codespaces. From your repo, click Code → Codespaces tab → Create codespace on main. It takes a while to load your editor in the browser. This is basically a VS Code editor connected to your repo.
3. From the Extensions view, install Claude Code.
4. Authenticate with Claude.
5. Open Claude and prompt it to create an API Reference doc using the YAML.
6. The prompt:
  `Generate an API Reference document from this OpenAPI YAML,
   with an Introduction, Authentication section, and one section
   per endpoint including request/response examples.`
7. It autogenerates with an introduction, authentication, and your endpoints section.
8. Additionally, you can prompt it to create cURL requests for each of the endpoints.
9. I reviewed the generated content for accuracy against the spec. The "Human in the Loop" step to verify accuracy.

## Result
This is what a generated API Reference looks like: https://htmlpreview.github.io/?https://raw.githubusercontent.com/janetjotw/api-automated/main/docs/products-api-reference.html
