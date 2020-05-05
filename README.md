# Vega DEV helper

This project uses the nice autoreload feature of demoit to
provide an easy to setup dev environment for Vega files.

## Installation

Install go (1.14 min) then demoit :

```
go get -u github.com/dgageot/demoit
```

Then install it :

````
cd $HOME/go/src/github.com/dgageot/demoit
go install -mod=vendor
````

Also ensure that $HOME/go/bin is in your path

## Launch

````
demoit -dev .
````

go to http://localhost:8888/
