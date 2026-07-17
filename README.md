# python-hot-reload

Dev-time helpers to reload changed modules (`importlib.reload`), reimport dependents, and rebind live instances' `__class__`.

Primary entrypoint: `debug_reload_pymodules()` (formerly in PyKotor `utility/tricks.py`).

## Install

```bash
pip install -e .
pip install git+https://github.com/bodencrouch/python-hot-reload.git
```

Optional peer: [`LoggerPlus`](https://github.com/bodencrouch/LoggerPlus).

## Origin

Extracted from [PyKotor](https://github.com/bodencrouch/PyKotor) `utility/tricks.py`.

## License

LGPL-3.0-or-later
