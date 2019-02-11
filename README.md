<h1 align="center"> weather </h1>

<p align="center"> A php weather SDK.</p>

[![Build Status](https://travis-ci.org/summercake/weather.svg?branch=master)](https://travis-ci.org/summercake/weather)

## Installing

```shell
$ composer require summercake/weather -vvv
```

## Usage

```sh
// $key is amap.com api key
$w = new Weather($key);
$w->getWeather('city');
```

## Contributing

You can contribute in one of three ways:

1. File bug reports using the [issue tracker](https://github.com/Summercake/weather/issues).
2. Answer questions or fix bugs on the [issue tracker](https://github.com/Summercake/weather/issues).
3. Contribute new features or update the wiki.

_The code contribution process is not very formal. You just need to make sure that you follow the PSR-0, PSR-1, and PSR-2 coding guidelines. Any new code contributions must be accompanied by unit tests where applicable._

## License

MIT
