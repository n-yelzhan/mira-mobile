# mediland — shared Python code

Python code that is needed in more than one case. Examples:

- loading reference tables from [`universe_data/`](../universe_data/)
- common cleaning steps (column names, date formats)
- helper functions for the accounting policy rules

## Rule

Code starts inside a case. It moves here only when a second case needs the same thing. This keeps one version of the code instead of several copies.

## Usage

```python
from mediland.loaders import load_tariffs
```

_Empty for now. Code will be added when it is needed by more than one case._
