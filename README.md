# typer-examples
Example CLI tools created in python using typer, poetry and pipx 

## General
- `brew install pipx`
- `sudo pipx ensurepath --global` (this is to allow --global options)
- `pipx install poetry`
- `poetry config virtualenvs.in-project true` (this makes all venvs in the project)

## Calculator CLI
- `poetry new calculator-jms` run once
- `cd calculator-jms`
- `poetry add typer`
- `poetry shell`
- `typer calculator_jms.main utils docs --output DOCS.md --name calculator-jms`