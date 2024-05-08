# Kismet for OpenWRT 23 - Custom Build Repository

Welcome to the custom build repository for Kismet 2023 on OpenWRT 23. This repository provides the necessary stepts to build Kismet manually for OpenWRT 23. As of the 2023 release, Kismet is no longer included in the official OpenWRT repositories, necessitating manual compilation for users who wish to run this powerful network detection and monitoring tool on their devices.

## About Kismet

Kismet is an open-source network detector, packet sniffer, and intrusion detection system. It works with any wireless card that supports raw monitoring mode and can sniff 802.11a, 802.11b, 802.11g, and 802.11n traffic. Kismet is widely used for network diagnostics as well as for network security monitoring.

## Building Kismet Manually

To compile Kismet manually, please refer to the continuous integration (CI) pipeline script available in this repository. The CI script outlines all necessary steps, from setting up the environment and dependencies to compiling the Kismet packages.

### Steps Overview

1. **Setup the Build Environment**: Initialize the OpenWRT build environment.
2. **Download and Prepare Dependencies**: Ensure all necessary dependencies are installed.
3. **Run the Build Scripts**: Execute the build scripts to compile Kismet.

You can view the detailed process in the `.github/workflows/build.yml` file. This file provides an automated sequence of operations which can also be performed manually in a local development environment.

## Usage

Once compiled, the Kismet packages can be installed on any compatible OpenWRT 23 device. Detailed installation instructions are provided in the build output or can be inferred from standard OpenWRT package installation procedures.
