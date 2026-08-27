# Linux and Git Learning Docs

Documentation for the Linux Learning and Git and GitHub learning paths, built with Mintlify.

## Preview locally

### Prerequisites

- [Node.js](https://nodejs.org/) and npm
- Git

### Steps

1. Clone the repository and move into the project directory:

	```bash
	git clone <repository-url>
	cd <repository-directory>
	```

2. Install the Mintlify CLI:

	```bash
	npm install -g mint
	```

3. Start the local documentation server from the directory containing `docs.json`:

	```bash
	mint dev
	```

4. Open the preview in your browser:

	[http://localhost:3000](http://localhost:3000)

Keep the terminal running while you preview the site. Mintlify automatically refreshes the browser when you save documentation changes.

## Publish changes

Commit and push your changes to the repository. If the repository is connected to Mintlify, the documentation deployment runs automatically after pushing to the configured branch.

## Troubleshooting

- Run `mint update` if the CLI is outdated.
- Make sure `mint dev` is run from the project root where `docs.json` is located.
- Stop the preview server with `Ctrl+C`.

## Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify page metadata](https://www.mintlify.com/docs/organize/pages)
