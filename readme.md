# Private Website Using Pelican

Pelican is a python based static website generator.

## Quickstart

To create a virtual environment with pelican:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install "pelican[markdown]"

# to configure the start of the website
pelican-quickstart
```

To generate and review website:
```bash
pelican content
pelican --listen
```

The repo provides a makefile commands for ease of use. Run `make help` to view them.

I have updated the makefiles to publish to the `gh-pages` branch everytime I run `make github`.
