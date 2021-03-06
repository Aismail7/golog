# Aismail7 / Go Log

[![Go Reference](https://pkg.go.dev/badge/github.com/Aismail7/golog.svg)](https://pkg.go.dev/github.com/Aismail7/golog) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The `Aismail7/GoLog` package is a collection of functions in the go language for Log.

---

## Table of Contents

* [Install](#install)
* [Usage](#usage)
* [Full Example](#full-example)
* [Versioning](#versioning)
* [Authors](#authors)
* [License](#license)
* [Official Documentation for Go Language](#official-documentation-for-go-language)
* [More](#more)

---

## Install

To use The `Aismail7/GoLog` package, you must follow the steps below:

```sh
go get -u github.com/Aismail7/golog
```

## Usage

### Init

To use Init Func., The `Aismail7/GoLog` package will add/modify .gitignore file and add `logs/` and the last one will create a `logs` folder. Inside the `logs` folder will contain the log files based on the log file creation date. The contents of the first parameter (`logLevel`) are `all`, `error`, `success`, `warning`, & `info`. The first parameter (`logLevel`) is used for the log level to be stored in the log file. The second parameter is used to `limit` the number of log files created other than the day's log files.

```go
golog.Init("all", 15)
```

### Error

```go
golog.Error("Ismail Ahmad")
```

Output:

```sh
2021-02-15 18:45:18 [ ERROR ] Ismail Ahmad
```

### Success

```go
golog.Success("Ismail Ahmad")
```

Output:

```sh
2021-02-15 18:45:18 [ SUCCESS ] Ismail Ahmad
```

### Warning

```go
golog.Warning("Ismail Ahmad")
```

Output:

```sh
2021-02-15 18:45:18 [ WARNING ] Ismail Ahmad
```

### Info

```go
golog.Info("Ismail Ahmad")
```

Output:

```sh
2021-02-15 18:45:18 [ INFO ] Ismail Ahmad
```

## Full Example

Full Example can be found on the [Go Playground website](https://play.golang.com/p/zk2GlYUvClU).

## Versioning

I use [SemVer](https://semver.org/) for versioning. For the versions available, see the tags on this repository. 

## Authors

**Ismail Ahmad** - [Aismail7](https://github.com/Aismail7/)

## License

MIT licensed. See the LICENSE file for details.

## Official Documentation for Go Language

Documentation for Go Language can be found on the [Go Language website](https://golang.org/doc/).

## More

Documentation can be found [on https://go.dev/](https://pkg.go.dev/github.com/Aismail7/golog).
