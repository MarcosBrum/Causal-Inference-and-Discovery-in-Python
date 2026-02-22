# Set environment

This python environment is managed by [uv](https://docs.astral.sh/uv/). Install it from the `curl` command mentioned in the official documentation.

To create a virtual enviromnent, run

```bash
uv venv --python 3.12
uv init
uv add <packages>
```

To set an environment using an existing pyproject.toml file:

```bash
uv sync
```

`uv` will automatically create a `.venv` directory using the specified python version and a `uv.lock` file with all the dependencies.