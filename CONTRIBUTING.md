# Contributing to Nueramarcos/tinygrad

## Setup

```bash
git clone https://github.com/Nueramarcos/tinygrad.git
cd tinygrad
pip install -e .
```

## Smoke test

```bash
python3 -c "from tinygrad import Device; print(Device.DEFAULT)"
```

## Notes

- This is a personal fork of [tinygrad/tinygrad](https://github.com/tinygrad/tinygrad).
- Experimental AMD/RDNA work may live on feature branches.
- Open draft PRs for small, focused changes.