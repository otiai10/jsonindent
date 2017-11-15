JSON Indent for Go Just for Enjoying Code Golf :golf:

```go
// What I was doing
encoder := json.NewEncoder(w)
encoder.SetIndent("", "\t")
encoder.Encode(v)
```

```go
// I just want to do
jsonindent.NewEncoder(w).Encode(v)
```

[![Build Status](https://travis-ci.org/otiai10/jsonindent.svg?branch=master)](https://travis-ci.org/otiai10/jsonindent)
[![GoDoc](https://godoc.org/github.com/otiai10/jsonindent?status.svg)](https://godoc.org/github.com/otiai10/jsonindent)
