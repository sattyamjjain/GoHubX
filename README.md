# GoHub

GoHub is a simple Go project to demonstrate the basics of building and structuring a Go application.

## Project Structure

```
gohub/
├── go.mod
├── go.sum
├── greetings
│   ├── greetings.go
│   └── greetings_test.go
└── hello
    └── hello.go
```

## Getting Started

### Prerequisites

- Go 1.16 or later

### Installation

1. Clone the repository:

```bash
git clone https://github.com/sattyamjjain/gohub.git
cd gohub
```

2. Tidy up the dependencies:

```bash
go mod tidy
```

### Running the Application

```bash
go run hello/hello.go
```

### Running the Tests

```bash
go test ./greetings
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
