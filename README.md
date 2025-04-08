# Go Snippets for Zed IDE

A collection of Go snippets for the [Zed IDE](https://zed.dev) to improve your development speed and productivity.

## Features

This extension provides a comprehensive set of snippets for Go development, including:

- Package and import declarations
- Control structures (if, for, switch)
- Function and method declarations
- Common Go patterns
- HTTP server code
- Testing helpers
- And much more!

## Installation

### Method 1

1. Go to Extensions menu in Zed IDE
2. Search for "go-snippets"
3. Click "Install"

### Method 2
1. Clone this repo:
```
git clone https://github.com/ayberkgezer/go-zed-snippets.git
```
2. Go to Extensions menu in Zed IDE
3. Click "Install Dev Extension"
4. Select the folder you cloned

## Usage

Start typing the snippet prefix (e.g., `go-func`) in a Go file and press `Tab` to expand the snippet.

## Available Snippets

| Prefix | Description |
|--------|-------------|
| `go-im` | Single import statement |
| `go-ims` | Multiple import block |
| `go-co` | Single constant |
| `go-cos` | Multiple constants block |
| `go-tyf` | Type function declaration |
| `go-tyi` | Type interface declaration |
| `go-tys` | Type struct declaration |
| `go-pkgm` | Package main with main function |
| `go-func` | Function declaration |
| `go-var` | Single variable declaration |
| `go-vars` | Multiple variables block |
| `go-switch` | Switch statement |
| `go-sel` | Select statement |
| `go-cs` | Case clause |
| `go-for` | For loop |
| `go-forr` | For range loop |
| `go-ch` | Channel declaration |
| `go-map` | Map declaration |
| `go-in` | Empty interface |
| `go-if` | If statement |
| `go-el` | Else branch |
| `go-ie` | If-else statement |
| `go-iferr` | If error check |
| `go-fp` | fmt.Println() |
| `go-ff` | fmt.Printf() |
| `go-lp` | log.Println() |
| `go-lf` | log.Printf() |
| `go-lv` | Log variable content |
| `go-tl` | t.Log() for tests |
| `go-tlf` | t.Logf() for tests |
| `go-tlv` | Log variable in tests |
| `go-make` | make() statement |
| `go-new` | new() statement |
| `go-pn` | panic() |
| `go-wr` | HTTP handler parameters |
| `go-hf` | http.HandleFunc() |
| `go-hand` | HTTP handler declaration |
| `go-rd` | http.Redirect() |
| `go-herr` | http.Error() |
| `go-las` | http.ListenAndServe() |
| `go-sv` | http.Serve() |
| `go-go` | Anonymous goroutine |
| `go-gf` | Goroutine function call |
| `go-df` | Defer statement |
| `go-tf` | Test function |
| `go-tm` | TestMain function |
| `go-bf` | Benchmark function |
| `go-ef` | Example function |
| `go-tdt` | Table-driven test |
| `go-finit` | init function |
| `go-fmain` | main function |
| `go-meth` | Method declaration |
| `go-helloweb` | Hello world web app |
| `go-sort` | Sort implementation |

## Examples

### Function declaration
Type `go-func` and press Tab:
```go
func name(param type) returnType {
    // Your code here
}
```

### If error check
Type `go-iferr` and press Tab:
```go
if err != nil {
    return nil, err
}
```

### HTTP handler
Type `go-hand` and press Tab:
```go
func handlerName(w http.ResponseWriter, r *http.Request) {
    // Your code here
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Author

Ayberk Gezer - [ayberkgezer@outlook.com](mailto:ayberkgezer@outlook.com)

## Repository

[https://github.com/ayberkgezer/go-zed-snippets](https://github.com/ayberkgezer/go-zed-snippets)
