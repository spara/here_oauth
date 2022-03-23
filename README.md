# HERE OAuth

`here_oauth` returns an oauth token for [HERE Technologies](https://platform.here.com) APIs.

## Requirements

A HERE [credential file](https://platform.here.com/management/projects).  

## Install

```bash
$ pip install here_oauth
```

## Usage

```python
from here_oauth import here_oauth

token = here_oauth.get_token("credential_file")
print(token)
```

