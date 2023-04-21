# Port sniffer:

To see available command:
cargo run -- -h

## Available options:

-a, --address <Address> The address that you want to sniff. Must be a valid ipv4 address.
Falls back to 127.0.0.1
-s, --start <ARG> The start port for the sniffer. (must be greater than 0)
-e, --end <ARG> The end port for the sniffer. (must be less than or equal to 65535)
-h, --help Prints help information

### Example:

cargo run -- -a 192.168.2.100
