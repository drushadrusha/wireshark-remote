# wireshark-remote
>Simple script to run wireshark capture on remote server.
>
>Usage:
>  wireshark-remote [remote user]@[remote ip] [interface on remote machine]
>
>Options:
>  -h   show help

## Installation
    wget https://raw.githubusercontent.com/drushadrusha/wireshark-remote/main/wireshark-remote
	chmod +x wireshark-remote

## Requirements
- Wireshark, obiviously.
- [You need to allow non-superusers be able to capture packets.](https://askubuntu.com/questions/748941/im-not-able-to-use-wireshark-couldnt-run-usr-bin-dumpcap-in-child-process)
