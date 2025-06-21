---
title: Install & Setup
---

## Install agno

We highly recommend:

- Installing `agno` using `uv` in a python virtual environment.

<Steps>
  <Step title="Install uv">
    Install `uv`, the fastest python package installer and dependency resolver.

    <CodeGroup>

    ```bash Mac
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

    ```bash Windows
    irm https://astral.sh/uv/install.ps1 | iex
    ```

    </CodeGroup>

  </Step>
  <Step title="Create and activate a virtual environment">
    Create a new virtual environment for your project and activate it.

    <CodeGroup>

    ```bash Mac
    uv venv --python 3.12
    source .venv/bin/activate
    ```

    ```bash Windows
    uv venv --python 3.12
    .venv\Scripts\activate
    ```

    </CodeGroup>
  </Step>
  <Step title="Install agno">
    <CodeGroup>

    ```bash Mac
    uv pip install -U agno
    ```

    ```bash Windows
    uv pip install -U agno
    ```

    </CodeGroup>

  </Step>
</Steps>

<br />

<Note>

If you encounter errors, try updating pip using `python -m pip install --upgrade pip`

</Note>

---

## Upgrade agno

To upgrade `agno`, run this in your virtual environment

```bash
uv pip install -U agno --no-cache-dir
```

---

## Setup Agno

Log-in and connect to agno.com using `ag setup`

```bash
ag setup
```
