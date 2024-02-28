# Chapter 0: Introduction

## Network Basics

The local network is created by your Wi-Fi/Ethernet router. The router is the device that’s connected to the internet provider.

- The router connects to the internet provider and gets its own IP address.
- It then creates the local network and assigns every device that connects to it a different local IP address. 
- Devices within the local network can communicate with each other, but not with devices in other local networks without specific configurations.

## Servers and IP Addresses

A server is a computer whose job is to serve us something. Servers have public IP addresses.

- Public IP addresses allow servers to be reached from outside the local network.
- Private IP addresses are used within local networks (e.g., home or office networks) and are not routable on the public internet.
- Devices within the same local network share the same private IP address range but have unique local IP addresses.
- Servers also have domain names, which are mapped to their IP addresses by DNS servers. 
- DNS servers translate domain names like `google.com` to IP addresses like `142.250.184.78`.

## Protocols and Communication

The language that computers use to talk to each other is called a protocol. The protocol that powers the internet is called Internet Protocol Suite, or TCP/IP.

- TCP (Transmission Control Protocol) ensures packets are delivered from client to server and vice versa.
- Internet Protocol (IP)  provides the addressing and routing mechanism for packets of data to be sent across networks.

# Chapter1: What is URL

## Understanding URLs

URLs are composed of several parts:

1. **Protocol**: Determines the protocol to be used (`http://` or `https://` for HTTP or HTTPS).
2. **Server Address**: Can be a domain name (`google.com`) or an IP address (`142.251.209.14`).
3. **Document Path**: Represents the document URL relative to the server root path (`/debugging/`).

Example:
- Protocol: `https://`
- Domain Name: `flaviocopes.com`
- Document Path: `/debugging/`

Combined, the URL is `https://flaviocopes.com/debugging/`.

## Web Servers

Web servers interpret requests and serve appropriate responses back to the client.