---
layout: post
title: "What is a Network?"
date: 2026-04-22 10:00:00 +0200
---

## What is a Network?

A network can be described as a system that connects two or more devices with each other to share or exchange data. These devices are connected through links, which may be wired (cables, optical fiber) or wireless (Wi-Fi, radio signals).

## What type of devices exist in a Network?

A network typically consists of devices like switches, routers, firewalls, laptops, PCs, servers and more.

### Switch
A switch is responsible for forwarding data between different hosts based on MAC addresses. MAC stands for Media Access Control. Each device has its own MAC address that comes from the NIC (Network Interface Card), which allows the device to connect to the network. Switches come in different port sizes – for example 8, 16, 24 or 48 ports. Each port can be connected to a device, making communication between them possible.

### Router
A router, on the other hand, connects networks with each other – for example a local network with the internet. It is also referred to as the gateway and uses IP addresses to route data based on the best or most efficient route available. Each device inside the network also has an IP address to be able to communicate with devices in other networks. So to summarize: a switch connects devices inside the local network using MAC addresses, while a router connects different networks using IP addresses.

### Firewall
A firewall can be used instead of a router if it offers routing capabilities, or in combination with a router, depending on the network setup. A firewall offers enhanced features like rules and policies to determine which traffic is allowed to enter or leave the network. It also provides additional security features to analyze traffic and help secure the local network.

### Server
Servers store, manage and distribute data across the network. In a client-server environment, clients connect to the server to retrieve or store data, or to access services that are centralized on the server – instead of having data spread across the network, which would make it harder to manage and access.

## What type of Networks exist?

There are different types of networks – the most common ones are LAN, MAN and WAN.

### LAN – Local Area Network
A LAN is what most of us interact with every day. It connects computers and devices within a local geographical area such as a home, school or office building. It consists of different devices like switches, routers, firewalls, laptops, PCs and servers – all connected to allow communication between them.

### MAN – Metropolitan Area Network
A MAN connects multiple LANs within a city. Imagine a company called Kahl Corporation, based in Hamburg with offices at different locations across the city. Connecting those offices with each other would form a MAN.

### WAN – Wide Area Network
A WAN connects networks across large distances. The internet itself is often referred to as the largest WAN in existence, as it connects countless individual networks across the globe. Unlike a LAN where you own the infrastructure, a WAN typically uses leased lines or the internet as the underlying transport – which is one of the reasons why technologies like VPN exist. But more on that in a later article.

## What type of topologies exist inside a network?

A network topology describes how devices are physically or logically arranged and connected with each other. The topology affects how data flows through the network and how resilient the network is in case of a failure. The most common topologies are Bus, Ring, Star and Mesh.

### Bus
In a bus topology, every device is connected to a single central cable. This is considered outdated and is no longer common in modern networks. The reason is simple – if the central cable fails at any point, communication between all devices breaks down.

### Ring
In a ring topology, each device is connected to exactly two other devices – one on each side – forming a closed loop. Data travels from device to device until it reaches its destination. The downside is that if one device fails, it can interrupt the entire data flow around the ring.

### Star
In a star topology, all devices are connected to a central device – typically a switch. This is by far the most common topology in modern networks. The advantage is that if one connection fails, only that device is affected. The rest of the network continues to function normally.

### Mesh
A mesh topology features multiple paths between devices. In a full mesh topology, every device has a direct connection to every other device, providing full redundancy. If one connection or device fails, data can be rerouted through an alternative path. Mesh topologies are common in WAN environments and the internet itself, where redundancy and reliability are critical.

## How do devices communicate with each other inside a Network?

In order for devices to communicate, they need to follow certain rules – these rules are called protocols. The most widely used protocol suite is TCP/IP. It is a standardized set of rules used by all manufacturers, which makes communication across different devices and networks possible. Think of it as a common language that allows devices to understand each other regardless of who made them. But more on protocols in a later article.
