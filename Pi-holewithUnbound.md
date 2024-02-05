# Pi-hole with Unbound Setup

## Project Overview

This repository contains instructions for setting up Pi-hole with Unbound for enhanced DNS filtering and security. The configuration is based on the tutorial by Crosstalk Solutions [The World's Greatest Pi-hole and Unbound Tutorial 2023](https://www.crosstalksolutions.com/the-worlds-greatest-pi-hole-and-unbound-tutorial-2023/#Lets_get_started) and the Pi-hole documentation [Unbound Integration Guide](https://docs.pi-hole.net/guides/dns/unbound/).

## Prerequisites

Ensure you have the following prerequisites before proceeding with the setup:

- Raspberry Pi (or similar device) with Raspbian OS installed.
- Basic knowledge of working with the command line.
- Internet connectivity on the device.

![2024-02-05_11-09](https://github.com/ericktafel1/RaspberryPiProjects/assets/97417443/a0522dac-7721-4297-b477-b8e673da14f1)


## Setup Instructions

Follow these steps to set up Pi-hole with Unbound:

### Step 1: Pi-hole Installation

Follow the Pi-hole installation instructions from [Pi-hole Documentation](https://docs.pi-hole.net/main/basic-install/).

### Step 2: Unbound Installation

Follow the Unbound installation instructions from Crosstalk Solutions [Tutorial](https://www.crosstalksolutions.com/the-worlds-greatest-pi-hole-and-unbound-tutorial-2023/#Lets_get_started).

### Step 3: Pi-hole and Unbound Integration

Configure Pi-hole to use Unbound as its upstream DNS server. Refer to the Pi-hole documentation [Unbound Integration Guide](https://docs.pi-hole.net/guides/dns/unbound/).

## Results

Now, ads, tracking and telemetry, malicious links, and other domains are blocked. The web interface allows for review of statistics and logs. I can later configure groups to whitelist or blacklist domains and devices. There is much more functionality but that is beyond the scope of this write-up.

![2024-02-05_11-41](https://github.com/ericktafel1/RaspberryPiProjects/assets/97417443/71f311a2-c2f3-45c4-b391-53f2fc22a89d)


## Additional Resources

- [Pi-hole Documentation](https://docs.pi-hole.net/)
- [Crosstalk Solutions](https://www.crosstalksolutions.com/)

