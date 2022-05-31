---
{"dg-publish":true,"permalink":"/tech-notes/programming/go/go/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Golang

- **[[Tech Notes/Programming/Go/Go|Go]]**
	- **Syntax**
		- [[Tech Notes/Programming/Go/Syntax/Types|Types]]
		- [[Tech Notes/Programming/Go/Syntax/Variables|Variables]]


## Overview

Golang is a compiled language. It is therefore fast. Not as fast as C or C++ but faster than Rust but with the memory safety of rust.

The compiled nature of Go makes programs written in Go very portable as the compiled programs don't need access to the source code.
It also benefits from the fact that Go does not need require any runtime language dependencies, unlike Python and JavaScript

Go is also **strongly typed** which means that variables must initiated with a declared type. This makes it possible to catch errors at compile time before the program is run.

Included with compiled Go programs is the Go Runtime. The primary purpose of this is to cleanup unused memory at runtime. This gives Go programs a very small memory footprint. This is unlike C++ and Rust who do not have automatic runtime memory optimisation.