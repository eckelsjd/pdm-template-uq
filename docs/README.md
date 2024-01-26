![Logo](assets/logo.svg)
[![pdm-managed](https://img.shields.io/badge/pdm-managed-blueviolet)](https://pdm-project.org)
[![PyPI](https://img.shields.io/pypi/v/pdm_template_uq?logo=python&logoColor=%23cccccc)](https://pypi.org/project/pdm_template_uq)
[![Python 3.11](https://img.shields.io/badge/python-3.11+-blue.svg?logo=python&logoColor=cccccc)](https://www.python.org/downloads/)

Use this template to set up your pdm project using:
```shell
pdm init https://github.com/eckelsjd/pdm-template-uq.git
```

**THE REST OF THIS README** will be populated with your project information. PLEASE IGNORE. You can delete
this text in your own readme file. Note that you will also have to manually fill in all broken links with your own
information (such as Github repo links, PyPI package links, etc.)

## Installation
You can install normally with:
```shell
pip install pdm-template-uq
```
If you are using [pdm](https://github.com/pdm-project/pdm) in your own project, then you can use:
```shell
cd <your-pdm-project>
pdm add pdm-template-uq
```
You can also quickly set up a development environment with:
```shell
# After forking this project on Github...
git clone https://github.com/<your-username>/pdm-template-uq.git
cd pdm-template-uq
pdm install  # reads pdm.lock and sets up an identical venv
```

## Quickstart
```python
import pdm-template-uq

pdm-template-uq.do_something()

print('Wow!')
```

## Contributing
See the [contribution](CONTRIBUTING.md) guidelines.

## Citations
Include any additional references for your project.

<sup><sub>Made with the [UQ pdm template](https://github.com/eckelsjd/pdm-template-uq.git).</sub></sup>

