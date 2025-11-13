# Key-Value Store - Fast CLI data storage and retrieval

**Package**: `@core/kv`
**Version**: 0.1.0
**Repository**: `pkg-core-kv`

## Overview

Key-Value Store - Fast CLI data storage and retrieval

## Installation

### Prerequisites

No external dependencies required.

### Using pkg-cli

```bash
# Install from GitHub
pkg-cli install @core/kv

# Or install from local source
cd ~/.pkgs
stow kv
```

## Usage

### Key-Value Store

Fast CLI-based key-value data storage and retrieval.

```bash
# Set a value
kv set mykey "my value"

# Get a value
kv get mykey

# List all keys
kv list

# Delete a key
kv delete mykey
```

## Configuration

Configuration files are typically stored in:
- `~/.config/kv/` - User configuration
- `~/.local/share/kv/` - Application data

## Uninstallation

```bash
# Using pkg-cli
pkg-cli uninstall @core/kv

# Or manual unstow
cd ~/.pkgs
stow -D kv
```

## Development

See [CLAUDE.md](CLAUDE.md) for development guidelines and AI assistance instructions.

## License

MIT License - See [LICENSE](LICENSE) file for details.

## Support

- **Issues**: [GitHub Issues](https://github.com/andronics/pkg-core-kv/issues)
- **Discussions**: [GitHub Discussions](https://github.com/andronics/pkg-core-kv/discussions)
- **Documentation**: [pkgs ecosystem docs](https://github.com/andronics/.pkgs)

## Version History

See [CHANGELOG.md](CHANGELOG.md) for version history.
