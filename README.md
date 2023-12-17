# Quick WireGuard VPN docker compose setup

## Prerequisites
Before starting, ensure you have the following prerequisites:
- Docker installed on your system.

## Configuration
1. Replace the placeholders in `.env` with your desired values. At least the `SERVERURL` has to be changed to the public IP of the server.
2. Start the WireGuard server using `docker compose up -d`
3. Display the client QR code with `./show-qr-code.sh 1` where 1 is the name of the first automatically created peer name (peer1 actually)
4. Import the QR code in your peer and connect to your Wireguard server

