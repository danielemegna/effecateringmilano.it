# Effe Catering Milano

![logo](./logo-big.png)

## Dev Notes

```
$ docker build -t effecateringmilano .
$ docker run --rm -dp 26:80 --name effecateringmilano effecateringmilano
```

or

```
$ docker run --rm -itp 26:80 -v $PWD:/usr/share/nginx/html/ nginx:alpine
```
