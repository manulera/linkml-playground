## Reproducing


```bash
# install dependencies
poetry install

# activate venv
poetry shell

# validate
linkml-validate --schema schema.yaml -C Room rooms.tsv
```

With linkml 1.7.10, it shows `22 is not of type 'string' in /room_nam`, but `22` is a valid string.
