
# The Google Code-in API Client

API Documentation is at https://developers.google.com/open-source/gci/api

# Usage

./list_tasks.py --apikey APIKEY

./list_instances.py --apikey APIKEY

./csv_uploader.py --apikey APIKEY file.csv

Each script also supports other flags.  Use --help to see them.

# Prerequisites

The client library requires
[requests](http://www.python-requests.org/) to be installed.

You can install it with `pip` or `easy_install`
([instructions](http://www.python-requests.org/en/latest/user/install/))
or install your operating system specific package.  On Ubuntu or
Debian, it is in the `python-requests` package.

# API Keys

Organization Adminstrators can find their API key on their
[User Profile](https://codein.withgoogle.com/).

# Code Style

We follow the [Google Python Style
Guide](https://google.github.io/styleguide/pyguide.html) with a few
modifications to match the *Google internal* version.  The primary one is the
use of 2 space indents.

Use [yapf](https://github.com/google/yapf) to keep the code formatted nicely.
You can set up an auto-save hook in your editor, or run it manually:

```shell
# one time setup:
pip install yapf

# format files:
yapf -i *.py
```

# Bugs/Support

To report bugs, please email [gci-support@google.com](mailto:gci-support@google.com).
