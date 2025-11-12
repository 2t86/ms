# mysize

A simple CLI tool for managing clothing size information.

## Overview

`mysize` is a command-line tool for recording and managing your favorite clothing brands, models, and size information. Perfect for referencing past purchases when shopping online or in stores.

## Installation

```bash
# Clone the repository
git clone <repository-url>
cd ms

# Add bin directory to PATH (optional)
export PATH="$PATH:$(pwd)/bin"
```

## Usage

### Add Items

```bash
# Interactive mode
mysize add outerwear

# Direct add with options
mysize add tops -b "Uniqlo" -m "Supima" -s "L" -c 55 -l 70
```

### List Items

```bash
# List all items
mysize list

# List by category
mysize list tops

# Simple format
mysize list --simple
```

### Edit and Delete Items

```bash
# Edit an item
mysize edit 5

# Delete an item
mysize delete 3
```

## Supported Categories

- `outerwear` - Jackets, coats, etc.
- `tops` - Shirts, t-shirts, etc.
- `bottoms` - Pants, jeans, etc.
- `footwear` - Shoes

## License

MIT
