## Quarto Dashboard Commands

This repo uses a project virtual environment and a registered Jupyter kernel named `dataxplore-venv`.

### Render a dashboard

```bash
quarto render src/penguins/penguins.qmd
```

### Live preview while editing

```bash
quarto preview src/penguins/penguins.qmd --no-browser --no-watch-inputs
```

### Basic dashboard example

```bash
quarto render src/basic/basic.qmd
```

### Notes

- The dashboard files are pinned to the `dataxplore-venv` kernel.
- If you add a new dashboard, set `jupyter: dataxplore-venv` in the YAML front matter so Quarto uses the same environment.
