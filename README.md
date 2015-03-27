# Boilerplate JS

This is a template framework for building JavaScript libraries.

## Requirements

* `node`
* `make`
* `python`

## Code design patterns

	var <module variable> = (function(<dependency local variable>*) {
		<module body>
		return <module value>
	})(<dependency global variable>*);

## To establish dependencies

	// @require "widget.js"

