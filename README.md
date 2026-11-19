# koala-mantids-5d-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m koala_mantids_5d_kit.cli --help
```

```python
from koala_mantids_5d_kit.core import KoalaMantids5dTool

tool = KoalaMantids5dTool()
print(tool)
```

## Layout

```
koala_mantids_5d_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 koala-mantids-5d
