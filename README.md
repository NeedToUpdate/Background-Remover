## Usage

1. (Optional) Create virtual env

```
    python -m venv .venv
```

and activate it based on your OS.

2. Install prerequisites

```python
    pip install -r ./requirements.txt
```

3. Add images into the /input folder
4. Run bg_remover.py

```python
 > python bg_remover.py
```

5. Find images with backgrounds removed in the output folder

---

You can specify different input and output folders with the flags:

```
    python bg_remover.py --input-path ../path/to/input --output-path ./path/to/output
```
