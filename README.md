Tweepy: Twitter for Python!
======

[![PyPI Version](https://img.shields.io/pypi/v/tweepy?label=PyPI)](https://pypi.org/project/tweepy/)
[![Python Versions](https://img.shields.io/pypi/pyversions/tweepy?label=Python)](https://pypi.org/project/tweepy/)
[![DOI](https://zenodo.org/badge/244025.svg)](https://zenodo.org/badge/latestdoi/244025)

[![Test Status](https://github.com/tweepy/tweepy/workflows/Test/badge.svg)](https://github.com/tweepy/tweepy/actions?query=workflow%3ATest)
[![Coverage Status](https://img.shields.io/coveralls/tweepy/tweepy/master.svg?style=flat)](https://coveralls.io/github/tweepy/tweepy?branch=master)

# Twitter API v2 Tweepy Integration

This repository demonstrates how to post a tweet using the Tweepy library with Twitter API v2. The script authenticates using OAuth 2.0 Bearer Token and posts a simple tweet.

## Prerequisites

- Python 3.6+
- Tweepy library
- Twitter Developer Account

## Setup

### 1. Enable Developer Account

Follow the instructions to enable your developer account:
[Enable Developer Account](https://developer.x.com/en/docs/authentication/oauth-1-0a/api-key-and-secret)

### 2. Login to Developer Account

Login to your developer account to get your API credentials:
[Developer Dashboard](https://developer.x.com/en/portal/dashboard)

### 3. Install Tweepy

Install the Tweepy library using pip:

```sh
pip install tweepy
```

### Usage
1. Replace Credentials
```sh
API_KEY = 'API_KEY'
API_KEY_SECRET = 'API_KEY_SECRET'
ACCESS_TOKEN = 'ACCESS_TOKEN'
ACCESS_TOKEN_SECRET = 'ACCESS_TOKEN_SECRET'
BEARER_TOKEN = 'BEARER_TOKEN'
```

2. Run the Script
run the script:
```sh
python main.py
```

To use the `tweepy.asynchronous` subpackage, be sure to install with the
`async` extra:

    pip install tweepy[async]

You can also use Git to clone the repository from GitHub to install the latest
development version:

    git clone https://github.com/tweepy/tweepy.git
    cd tweepy
    pip install .

Alternatively, install directly from the GitHub repository:

    pip install git+https://github.com/tweepy/tweepy.git

Python 3.7 - 3.11 are supported.

Links
-----

- [Documentation](https://tweepy.readthedocs.io/en/latest/)
- [Official Twitter Page](https://x.com/tweepy_labs)
- [Twitter API Documentation](https://developer.twitter.com/en/docs/twitter-api)

