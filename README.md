# MoonPhase
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/janczer/MoonPhase/master/LICENSE)

Package MoonPhase allow calculate the phase of Moon, and other related variables. It's base on [php-moon-phase](https://github.com/solarissmoke/php-moon-phase)

## Installation

To install the package on your seysetm, run

```
go get github.com/abakum/MoonPhase
```

## Quick Start

```
time := time.Date(2007, 10, 1, 24, 0, 0, 0, time.UTC)
//time := time.Now()
m := MoonPhase.New(time)
```

## License

MoonPhase is released under the MIT License. It is copyrighted by Ivan Menshykov and
the contributors acknowledged below.

## Acknowledgments

This package's code and documentation are very closely derived [php-moon-phase](https://github.com/solarissmoke/php-moon-phase)
PHP class for calculating the phase of the Moon created by Samir Shah.
