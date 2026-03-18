# public-apis-ultra

[![Stars](https://img.shields.io/github/stars/anthropics/anthropic-cookbook?style=social)](https://github.com/anthropics/anthropic-cookbook)
[![Forks](https://img.shields.io/github/forks/anthropics/anthropic-cookbook?style=social)](https://github.com/anthropics/anthropic-cookbook)
[![Issues](https://img.shields.io/github/issues/anthropics/anthropic-cookbook)](https://github.com/anthropics/anthropic-cookbook)
[![License](https://img.shields.io/github/license/anthropics/anthropic-cookbook)](https://github.com/anthropics/anthropic-cookbook)

## The next evolution of public-apis

**A collective list of free APIs, now with superpowers.**

## Why switch?

We've taken the beloved [public-apis](https://github.com/public-apis/public-apis) and made it even better. Here's how:

| Feature | public-apis | public-apis-ultra |
|---------|-------------|-------------------|
| Number of APIs | 1000+ | 2000+ |
| Automated Health Checks | ❌ | ✅ |
| Enhanced Search & Filtering | Basic | Advanced |
| Better Categorization | Basic | Enhanced |
| Community Tools | Basic | Advanced |

## Quickstart

### Using the list

Browse the list in the [README](README.md) or on our website: [https://public-apis-ultra.github.io](https://public-apis-ultra.github.io)

### Using the CLI

Install the CLI tool:

```bash
npm install -g public-apis-ultra
```

Then search for APIs:

```bash
public-apis-ultra search "weather"
```

### Using the API

Access the list programmatically:

```bash
curl https://api.public-apis-ultra.github.io/entries
```

## Architecture

Our project is structured as follows:

- `README.md`: The main list of APIs, categorized and with status indicators.
- `api/`: A RESTful API server that serves the list in JSON format.
- `cli/`: The command-line interface tool.
- `community/`: Tools for community management and contribution handling.

## Usage

### Browsing the list

The list is organized by categories. Each API entry includes:

- **API**: The name of the API.
- **Description**: A brief description.
- **Auth**: The type of authentication required (if any).
- **HTTPS**: Whether the API supports HTTPS.
- **CORS**: Whether the API supports CORS.
- **Status**: Whether the API is currently up (checked periodically).

### Using the CLI

The CLI tool allows you to search and filter APIs from the terminal.

Examples:

```bash
# Search for APIs
public-apis-ultra search "database"

# Filter by category
public-apis-ultra filter --category "Weather"
```

## Contributing

We welcome contributions! Here's how:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes to the list or tools.
4. Submit a pull request.

### Adding a new API

To add a new API, simply edit the `README.md` file and add your entry in the appropriate category.

## Migrating from public-apis

Switching is easy! Here's what you need to do:

1. Bookmark our website or clone our repository.
2. Use our enhanced search and filtering.
3. Enjoy the automated health checks and better categorization.

No data loss, no complicated setup. Just better features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.