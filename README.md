# Effe Catering Milano

![logo](./logo-big.png)

## Dev Notes

```
$ docker build -t effecateringmilano .
$ docker run --rm -dp 26:80 --name effecateringmilano effecateringmilano
```

or

```
$ docker run --rm -it -p 26:80 -v $PWD:/www fnichol/uhttpd
```
