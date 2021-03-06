# Config [![wercker status](https://app.wercker.com/status/b4e8561d9a711afcb016bf0018e83897/s/ "wercker status")](https://app.wercker.com/project/bykey/b4e8561d9a711afcb016bf0018e83897) [![GoDoc](https://godoc.org/github.com/olebedev/config?status.png)](https://godoc.org/github.com/olebedev/config)

Package config provides convenient access methods to configuration
stored as JSON, TOML or YAML.

This is a fork of the [original version](https://github.com/moraes/config).
This version extends the functionality of the original without losing compatibility.
Major features added:

- [`Set(path string, value interface{})`](http://godoc.org/github.com/olebedev/config#Config.Set) method
- [`Env()`](http://godoc.org/github.com/olebedev/config#Config.Env) method, for OS environment variables parsing
- [`Flag()`](http://godoc.org/github.com/olebedev/config#Config.Flag) method, for command line arguments parsing
- [`U*`](https://godoc.org/github.com/olebedev/config#Config.UBool) methods

Example and more information you can find [here](http://godoc.org/github.com/olebedev/config).
