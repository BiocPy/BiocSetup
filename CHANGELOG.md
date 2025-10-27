# Changelog

## Version 0.3.2
- Python 3.9 has reached its EOL, Update GitHub actions to run from 3.10 - 3.14.

## Version 0.3.0 - 0.3.1

- Use Trusted publisher workflow to publish packages to PyPI.
- Update ruff configuration.
- Streamlining github actions for testing on various platforms and python versions.
- Optional codecov setup to upload coverage reports.
- Support reStructuredText in addition to markdown.
- Added workflow for developing python packages.

## Version 0.2.0

- Rename github actions to `run-tests` & `publish-pypi`.

## Version 0.1.1 - 0.1.2

- Minor changes to improve user experience.
- Replace `myst_nb` and `myst_parser`.

## Version 0.1.0

- Uses PyScaffold with Markdown extension for base project structure
- Configures GitHub Actions for testing and PyPI publishing
- Sets up pre-commit hooks
- Configures documentation with:
  - MyST-NB for Jupyter notebook support
  - Furo theme
  - Type hints documentation
- Adds Ruff configuration for consistent code formatting
- Creates README
