# UDP Flood

This project is a simple implementation of a UDP flood attack. It is intended for educational purposes only. Please use it responsibly and only on systems you have permission to test.

## Features

- Sends a large number of UDP packets to a specified target.
- Configurable target IP address and port.
- Adjustable packet size and flood duration.

## Requirements

- Python 3.x

## Usage

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/UDP-FLOOD.git
    ```

2. Navigate to the project directory:
    ```
    cd UDP-FLOOD
    ```

3. Run the script:
    ```
    python udp_flood.py <target_ip> <target_port> <packet_size> <duration>
    ```

    Example:
    ```
    python udp_flood.py 192.168.1.1 80 1024 60
    ```

    This will send UDP packets of size 1024 bytes to the target IP `192.168.1.1` on port `80` for `60` seconds.

## Disclaimer

This tool is for educational purposes only. Do not use it to attack any network or system without permission. The author is not responsible for any misuse of this tool.
