![version](https://img.shields.io/badge/version-20%2B-E23089)
![platform](https://img.shields.io/static/v1?label=platform&message=mac-intel%20|%20mac-arm%20|%20win-64&color=blue)
[![license](https://img.shields.io/github/license/miyako/list)](LICENSE)
![downloads](https://img.shields.io/github/downloads/miyako/list/total)

# list
Support toolbox list commands in project mode (namespace: `list`)

|command|function name|
|-|-|
|ARRAY TO LIST||
|LIST TO ARRAY||
|load list||
|SAVE LIST||

## design

* if possible, use `lists.json` on server side, in standard location
* otherwise use `lists.json` on server side, in custom location
* internally use `LIST TO BLOB` and `BLOB to list`
* save and restore icon, font, parameters
* save and restore properites (enterable, styles, color)
* thread safe
