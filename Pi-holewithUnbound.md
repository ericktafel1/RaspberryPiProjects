# Pi-hole with Unbound Setup

## Project Overview

This repository contains instructions for setting up Pi-hole with Unbound for enhanced DNS filtering and security. The configuration is based on the tutorial by Crosstalk Solutions [The World's Greatest Pi-hole and Unbound Tutorial 2023](https://www.crosstalksolutions.com/the-worlds-greatest-pi-hole-and-unbound-tutorial-2023/#Lets_get_started) and the Pi-hole documentation [Unbound Integration Guide](https://docs.pi-hole.net/guides/dns/unbound/).

## Prerequisites

Ensure you have the following prerequisites before proceeding with the setup:

- Raspberry Pi (or similar device) with Raspbian OS installed.
- Basic knowledge of working with the command line.
- Internet connectivity on the device.

## Setup Instructions

Follow these steps to set up Pi-hole with Unbound:

### Step 1: Pi-hole Installation

Follow the Pi-hole installation instructions from [Pi-hole Documentation](https://docs.pi-hole.net/main/basic-install/).

### Step 2: Unbound Installation

Follow the Unbound installation instructions from Crosstalk Solutions [Tutorial](https://www.crosstalksolutions.com/the-worlds-greatest-pi-hole-and-unbound-tutorial-2023/#Lets_get_started).

### Step 3: Pi-hole and Unbound Integration

Configure Pi-hole to use Unbound as its upstream DNS server. Refer to the Pi-hole documentation [Unbound Integration Guide](https://docs.pi-hole.net/guides/dns/unbound/).

## Configuration Files

This section provides an overview of key configuration files included in this repository:

- `pihole-setup.sh`: Shell script for Pi-hole installation.
- `unbound-setup.sh`: Shell script for Unbound installation.
- `pihole-unbound-integration.sh`: Shell script for configuring Pi-hole to use Unbound.

## Additional Resources

- [Pi-hole Documentation](https://docs.pi-hole.net/)
- [Crosstalk Solutions](https://www.crosstalksolutions.com/)

## License

This project is licensed under the [MIT License](LICENSE).

