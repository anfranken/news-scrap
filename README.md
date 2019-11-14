# news-scrap

## Getting Started

### Prerequisites

Follow the installation instructions for Python:

- <https://realpython.com/installing-python/>

Install [pipenv](https://github.com/pypa/pipenv) to make dealing with requirements and virtual environments easier.

```bash
$ pip install --upgrade --user pipenv
```

### Installation

Clone this repository and install requirements with pipenv:

```bash
$ git clone https://github.com/anfranken/news-scrap.git && cd news-scrap
$ pipenv install --dev
# Activate the project's virtual environment
$ pipenv shell
```

To verify the installation was successful, you can type:
```bash
$ (news-scrap) news-please -h
usage: news-please [-h] [-c CFG_FILE_PATH] [-resume] [-reset-elasticsearch]
                   [-reset-mysql] [-reset-json] [-reset-all] [-no-confirm]

A generic news crawler and extractor.
```
