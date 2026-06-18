# Nueramarcos Fork of tinygrad

This repository is a personal fork of [tinygrad/tinygrad](https://github.com/tinygrad/tinygrad).

## Quick start

```bash
git clone https://github.com/Nueramarcos/tinygrad.git
cd tinygrad
pip install -e .

# Basic smoke test
python3 -c "
from tinygrad import Device
print('✅ Device.DEFAULT =', Device.DEFAULT)
"
```

## Notes

- Experimental AMD/RDNA and emulator work may live on feature branches.
- Upstream: https://github.com/tinygrad/tinygrad
- Maintained by [Nueramarcos](https://github.com/Nueramarcos)