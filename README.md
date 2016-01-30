### ES6 => ES5 -- a performance exploration.

* [x] babel + browserify + uglify
* [x] babel + rollup + uglify
* [x] typescript + uglify
* [x] traceur compiler + uglify
* [x] closure compiler

---------------------------------


#### Results

| Tools                        | File Size (bytes) |
| -----------------------------|-------------------|
| closure                      | 15213             |
| babel + rollup + uglify      | 15925             |
| typescript + uglify          | 19455             |
| babel + browserify + uglify  | 20366             |
| traceur + browserify + uglify| 98117             |


--------------------------------


#### Contributing

##### Building Samples

`make <babel | closure | typescript | rollup | traceur>`

##### View Demo

`cd src && python -m SimpleHTTPServer`

visit localhost:8000/
