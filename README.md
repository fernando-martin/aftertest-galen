# Galen example

## Requirements
* Ant 1.9.3
* Galen 2.1.2, <a href="http://galenframework.com/download/" target="_blank">download</a>

## Quick start

* Download Chromedriver
 
```
$ ant
```

* Run tests

```
$ galen test tests/example.test --htmlreport "reports" -Dwebdriver.chrome.driver=lib/chromedriver
```
