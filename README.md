### Golang testmodule

A simple Go module with a `SayHello` function to print greetings.

### 📦 Installation

Use `go get` to install the module:

```bash
go get github.com/neelkumar01/testmodule
```
This will download the module and add it to your project dependencies.

### ⚙️ Usage
Import the module in your Go code:

```bash
package main

import (
    "github.com/neelkumar01/testmodule"
)

func main() {
    testmodule.SayHello("Neel")
}
```

### 🧩 Output
```bash
Hello Neel
```

### 🗂️ Project structure
```bash
testmodule/
├── code.go
└── go.mod

```
