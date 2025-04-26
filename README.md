# README

## Setup

```shell
# Install uv
curl -LsSf https://astral.sh/uv/install.sh | sh
# Create .env file
touch .env
```

Edit .env and add your api key

```
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

```shell
# Load .env and read API key as environment variable
set -a
source .env
set +a
```
