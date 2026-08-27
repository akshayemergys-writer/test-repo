# Docker and Kubernetes Learning

Documentation for Docker containers and Kubernetes orchestration, built with Mintlify.

## Preview locally

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm install -g mint
```

Run the preview from the project root, where `docs.json` is located:

```bash
mint dev
```

Open `http://localhost:3000` in your browser.

## Publish changes

Commit and push changes to the configured deployment branch. Mintlify will build and publish the documentation for the connected project.

## Troubleshooting

- Run `mint update` if the CLI is outdated.
- Run `mint dev` from the directory containing `docs.json`.
- Stop the local preview with `Ctrl+C`.
