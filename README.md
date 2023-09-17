# port-pulse

port-pulse is a TCP port scanner CLI written in Rust. It allows you to quickly and efficiently scan a range of TCP ports on a target host to check for open ports and potential vulnerabilities. This tool is designed to be fast, reliable, and easy to use, making it a valuable addition to your network security toolkit.

## Features

- **Fast and Efficient:** port-pulse is optimized for speed, allowing you to scan a wide range of ports on a target host quickly.

- **Flexible Port Range:** You can specify a range of ports to scan, or you can scan a single port. This flexibility makes it suitable for various use cases.

- **Concurrency:** port-pulse utilizes concurrency to scan multiple ports simultaneously, further speeding up the scanning process.

- **Customizable Timeout:** You can set a timeout value to control how long port-pulse waits for a response from each port, making it adaptable to different network conditions.

## Installation

To use port-pulse, you'll need to have Rust installed on your system. If you don't have Rust installed, you can download it from [Rust's official website](https://www.rust-lang.org/).

Once you have Rust installed, you can install port-pulse using Cargo, Rust's package manager, with the following command:

```bash
cargo add port-pulse
```
OR

Add the following line to your Cargo.toml:

```bash
port-pulse = "0.2.0"
```

## Usage

-j to select how many threads you want
-h or -help to show help message

Example:

```bash
port-pulse -j 1000 <ip-address>
```
OR

```bash
port-pulse -h
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Disclaimer
port-pulse is intended for legitimate security and network administration purposes. Please ensure that you have the necessary permissions to scan a target host, as unauthorized scanning may be illegal in some jurisdictions. Use this tool responsibly and only on systems you own or have explicit permission to scan. The developers and contributors of port-pulse are not responsible for any misuse or unlawful activities carried out using this tool.





