# dccs_logo

A python module for creating a logo for the dccs team.

## Installation

To install the dccs_logo module, use pip:

```
pip install dccs_logo
```

## Usage

To use the dccs_logo module, import it and use the `dccs_logo.logo()` function:

```python
from dccs_logo import logo
from rich import print
author = "Team dccs"
tools = "test"
version = 1.0
github = "team-dccs"

logo = logo(author, tools, version, github)
print(logo)
```

## logo2

To use the dccs_logo module, import it and use the `dccs_logo.logo2()` function:
```python

from dccs_logo import logo2
from rich import print
author = "Team dccs"
tools = "test"
version = 1.0
github = "team-dccs"

logo = logo2(author, tools, version, github)
print(logo)
```

This will print out the dccs logo with the given parameters.

## Contributing

If you would like to contribute to the dccs_logo module, please fork the repository and submit a pull request.

## License

The dccs_logo module is released under the MIT License.
