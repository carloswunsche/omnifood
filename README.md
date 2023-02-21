<div align="center">
  <a href="https://cw-omnifood.netlify.app">
    <img width="50%" src="img/omnifood-logo.png" alt="Omnifood Logo by Jonas Schmedtmann" title="Omnifood Logo by Jonas Schmedtmann">
  </a>
</div>
<br/>
<div align="center">
  <img src="https://img.shields.io/website?up_message=online&amp;url=https%3A%2F%2Fcw-omnifood.netlify.app" alt="Website">
</div>

---

(What is?) Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
