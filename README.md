# HTTP status check

## Installation from sources

### Install Go

```
bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)
source ~/.gvm/scripts/gvm
sudo apt-get install bison
gvm install go1.4 -B
gvm use go1.4
export GOROOT_BOOTSTRAP=$GOROOT
gvm install go1.7 --prefer-binary
gvm use go1.7 --default
```

### Install packages

```
go get github.com/jawher/mow.cli
go get github.com/parnurzeal/gorequest
go get gopkg.in/go-playground/pool.v3
```
