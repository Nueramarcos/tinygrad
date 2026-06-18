# Nueramarcos/tinygrad

Personal fork of [tinygrad/tinygrad](https://github.com/tinygrad/tinygrad).

## Quick Start

```bash
git clone https://github.com/Nueramarcos/tinygrad.git
cd tinygrad
pip install -e .

# Smoke test
python3 -c "
from tinygrad import Device, Tensor
print('✅ Device:', Device.DEFAULT)
print('✅ Tensor test:', Tensor([1,2,3]).sum().item())
"
```

## Notes

- Experimental AMD/RDNA and emulator work may live on feature branches.
- Upstream: https://github.com/tinygrad/tinygrad
- Maintained by [Nueramarcos](https://github.com/Nueramarcos)