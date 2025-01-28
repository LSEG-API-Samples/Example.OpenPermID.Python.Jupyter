# Example.OpenPermID.Python.Jupyter

## Overview

This example demonstrates how to use a Python Open PermID library. The library covers all features of Open PermID APIs including Record Matching, Entity Search, and Intelligent Tagging. 

PermID is a shortening of “Permanent Identifier” which is a machine-readable number assigned to entities, securities, organizations (companies, government agencies, universities, etc.), quotes, individuals, and more. It is specifically designed for use by machines to reference related information programmatically. Open PermID is publicly available for free at [https://permid.org/](https://permid.org/).

The Python OpenPermID is available on [pypi.org](https://pypi.org/project/OpenPermID/). It can be installed via the following **pip** command.

```
pip install OpenPermID
```
To use the Python OpenPermID, the application needs to create an OpenPermID object and set an access token to it. The access token can be retrieved after login to the [Open PermID](https://permid.org/) website.


```python
from OpenPermID import OpenPermID

opid = OpenPermID()
opid.set_access_token("<ACCESS TOKEN>")
```
For more information, please refer to this [Introduction to the Open PermID Python library](https://developers.lseg.com/en/article-catalog/article/introduction-to-the-open-permid-python-library) article.
