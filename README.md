# pywe-component

Wechat Component Module for Python.

# Installation

```shell
pip install pywe_component
```

# Usage

```python
from pywe_component import get_pre_auth_url, get_mobi_pre_auth_url
```

# Method

```python
def get_pre_auth_url(component_appid, pre_auth_code=None, redirect_uri=None, auth_type=3, biz_appid='', mobi=False)

def get_mobi_pre_auth_url(component_appid, pre_auth_code=None, redirect_uri=None, auth_type=3, biz_appid='')
```
