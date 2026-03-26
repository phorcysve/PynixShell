
### Prerequisites
- Python 3.8 or higher.
- No external dependencies required (uses standard library).

### Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd MAIN
   ```

2. (Optional) Build with Docker:
   ```bash
   docker build -t myshell .
   docker run -it myshell
   ```

## Usage

### Interactive Mode

Launch the shell for interactive use:
```bash
python3 sh.py
```

### Script Mode

Run a shell script file:
```bash
python3 sh.py your_script.sh
```

### Running Tests

Execute the test suite using `pytest`:
```bash
./test.sh
```
Or directly:
```bash
pytest test/
```

### Contributing

Contributions are welcome! Please refer to [contrib.md](contrib.md) for guidelines and the [roadmap.md](roadmap.md) for planned features.

## License

This project is licensed under the terms found in the [license](license) file.
