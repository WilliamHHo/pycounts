# pycounts

Calculate word counts in a text file!

## Installation

```bash
pip install pycounts_whh
```

## Usage

`pycounts_whh` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_whh.pycounts_whh import count_words
from pycounts_whh.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. 
Please note that this project is released with a Code of Conduct. 
By contributing to this project, you agree to abide by its terms.

## License

`pycounts_whh` was created by William Ho. It is licensed under the terms
of the MIT license.

## Credits

`pycounts_whh` was created with 
[`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and 
the `py-pkgs-cookiecutter` 
[template](https://github.com/py-pkgs/py-pkgs-cookiecutter).