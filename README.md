# go-imgparse #

**Description**

A small go library to efficiently parse the resolution of various image format streams. Can used with any `io.Reader`.

**Current Content Type Support**

- gif
- jpeg
- png
- webp
- webpll
- more to come

**Installing**

```
go get github.com/vimeo/go-imgparse/imgparse
```

**API**

The API is a single function call:

```go
import "github.com/vimeo/go-imgparse/imgparse"

imgparse.ParseRes(input io.Reader, contenttype string)
```

The `input` argument is any reader, and `contenttype` is any of the types listed above.
