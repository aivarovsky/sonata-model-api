# Sonata Model API

## Overview

The Sonata Model API is a FastAPI application that generates embeddings of user queries for the Sonata project.

## Sonata project

| Repository | Description |
|---|---|
| [Sonata](https://github.com/aivarovsky/sonata-app) | Web application for searching music releases by describing their cover. |
| Sonata Model API | API for generating embeddings of user queries for the Sonata project. |
| [Sonata Cache](https://github.com/aivarovsky/sonata-cache) | In-memory user query cache for the Sonata project. |
| [Sonata Data Ingestor](https://github.com/aivarovsky/sonata-data-ingestor) | Data ingestor for the Sonata project. |

## Setup

1. Clone this repository to your local machine:

    ```bash
    git clone git@github.com:aivarovsky/sonata-model-api.git
    ```

2. Navigate to the project directory:

    ```bash
    cd sonata-model-api
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run `main.py`:

    ```bash
    python main.py
    ```

## License

This project is licensed under the [**Unlicense**](https://github.com/aivarovsky/sonata-model-api/blob/main/LICENSE).
