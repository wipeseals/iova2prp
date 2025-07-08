# iova2prp

[![Deploy static content to Pages](https://github.com/wipeseals/iova2prp/actions/workflows/static.yml/badge.svg)](https://github.com/wipeseals/iova2prp/actions/workflows/static.yml)

I/O Virtual Address to Physical Region Page Calculator

A web-based calculator that visualizes the conversion from IOVA (I/O Virtual Address) to NVMe PRP (Physical Region Page) in VFIO environments.

## Features

- Interactive parameter configuration for IOVA calculations
- Visual memory layout representation
- Code generation in multiple languages (C, Python, JavaScript, Zig)
- Real-time PRP1/PRP2 calculation based on transfer size and page boundaries

## Usage

Visit the live demo: [https://wipeseals.github.io/iova2prp/](https://wipeseals.github.io/iova2prp/)

Or run locally by serving the `index.html` file with any web server.

## License

MIT License - see [LICENSE](LICENSE) file for details.
