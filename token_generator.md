# Token Generator

This script generates a token using a specified coldkey and prints the signature and coldkey address.

## Prerequisites

- Python 3.x
- `bittensor` library

## Installation

1. **Install Python**: Download and install Python from [python.org](https://www.python.org/downloads/).

2. **Install Bittensor**: Use pip to install the `bittensor` library:
   ```bash
   pip install bittensor
   ```

## Usage

To run the script, use the following command:

```bash
python token_generator.py [coldkey]
```

Replace `[coldkey]` with your actual coldkey name. For example:

```bash
python token_generator.py mycoldkey
```

### Help

To view the usage instructions, run:

```bash
python token_generator.py -h
```

or

```bash
python token_generator.py --help
```

## Example

```bash
python token_generator.py example_coldkey
```

This will output the signature and coldkey address associated with `example_coldkey`.

## Error Handling

If an error occurs during execution, the script will print an error message to the console.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
