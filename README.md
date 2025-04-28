# README

## Setup

```shell
# Install uv
curl -LsSf https://astral.sh/uv/install.sh | sh

# install packages
uv sync

# Create .env file
touch .env
```

Edit .env and add your api key

```
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

## Run

```shell
uv run request_api.py
```
