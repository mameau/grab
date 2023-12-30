# grab
used for occasional leeching of archive.org links

requires xmllint with xpath support for queue build, queues can be run anywhere with a recent version of wget

```
./grab https://archive.org/download/picowesome-v1.1 PICO8Awesome
```

or exclude items
```
./grab https://archive.org/download/picowesome-v1.1 PICO8Awesome pico8-awesome.exclude
```
where .exclude is a list of filenames grepped during the generation of the wget queue
