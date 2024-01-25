# [package]: Rtc definitions

This package provides common Rtc structures and definitions, as used by the ASE project.

## Getting started

First, add the service runner package to your Go module:

```bash
go get github.com/VU-ASE/pkg-Rtc
```

> [!TIP]
> You can install a specific version like this: `go get github.com/VU-ASE/pkg-Rtc@v0.1.2` to improve reproducibility

Now in your Go code, you can use the exports as in this example:

```go
package main

import (
    // Import and rename
	rtc "github.com/VU-ASE/pkg-Rtc/src"
)

func main() {
    // Create a variable using the imported type
    a := rtc.Rtc{}
}

```