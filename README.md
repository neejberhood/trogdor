# trogdor

De neejberhood discord bot

## Running the bot locally

To run the bot locally, you need a `.env`file with contents:

```text
TOKEN=[INSERT BOT TOKEN HERE]
```

We'll try to find a better way to arrange this in due time. For now, this will have to do.

## Creating a PR

The repo is configured to run pylint on each PR, and will scream if it fails. So probably best to run it before creating a PR. Black will also run, and automatically create a commit if your code formatting differs. Feel free to use whatever locally, just like it formatted in a standard way in the repo.
