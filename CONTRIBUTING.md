# Contributing

## Development Setup

```bash
python -m venv .venv
source .venv/bin/activate

python setup.py install
pip install -e ".[dev]"
```

## Running Tests

```bash
python -m pytest
```