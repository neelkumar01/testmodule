### Golang testmodule

A simple Go module with a `SayHello` function to print greetings.

### 📦 Installation
Create a go.mod file in your project
```bash
go mod init testproject
```
Use `go get` to install the module:

```bash
go get github.com/neelkumar01/testmodule
```
This will download the module and add it to your project dependencies and you will be able to see 2 files, `go.mod` and `go.sum` being created in your project.

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
