### Movie task

```
Movie

id      title      year     language        run_time


1          kgf1      2008      kannada           160
2          kgf2      2020      kannada           165
3          kgf3      2026      kannada           167
4          kgf4      2028      kannada           168
5          kgf5      2030      kannada           169


```
http_request for adding new movie

url: localhost:8000/movie/
method:POST
body:{
    "title":"im game",
    "year":26,
    "language":"malayalam",
    "run_time":170
}
```

```
http_request for list all movie

url: localhost:8000/movie/
method:GET

```


```
http_request for fetching movie detail

url: localhost:8000/movie/3/
method:GET
```

```
http_request for update movie

url: localhost:8000/movie/6
method:PUT
body:{
    "title":"im game",
    "year":26,
    "language":"hindi",
    "run_time":168
}
```

```
http_request for delete movie`

url: localhost:8000/movie/4
method:DELETE
```