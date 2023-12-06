# Tracing DNS using Wireshark

## Project Overview

This project delves into the practical aspects of capturing and scrutinizing DNS (Domain Name System) packets associated with everyday web-surfing activities. By leveraging tools such as `nslookup` and `ipconfig`, we aim to provide a hands-on experience in uncovering the intricacies of communication between hosts and DNS servers during standard web browsing.

![Tracing DNS using Wireshark](https://github.com/HR-Fahim/DNS-Tracing-and-HTTP-Packet-Sniffing-with-Wireshark/assets/66734379/32a8c59f-aa8e-4cbd-b98e-708bd915ad1b)

## Exploration Highlights

- **Capture Methodology:** Employ Wireshark to intercept DNS packets generated as a result of web-surfing.

- **Cache Management:**
  - Utilize `ipconfig` to clear the DNS cache on the host.
  - Clear the browser cache to ensure a clean slate for precise packet capture.

- **Web Interaction:**
  - Initiate DNS requests by entering `www.google.com` in the web browser.

- **Packet Focus:**
  - Refine captured data by applying a Wireshark filter targeting DNS packets containing specific keywords (e.g., "google").

- **In-depth Analysis:**
  - Identify and scrutinize DNS request and response packets.
  - Dive into the details encapsulated within a DNS request packet.
  - Analyze the corresponding DNS response packet.

# Decoding HTTP Packets for Comprehensive Packet Stream Analysis

## Project Overview

Throughout the development and implementation of this project, several key milestones have been successfully achieved, enhancing the overall capabilities and usability of the packet stream analysis tool. The following aspects highlight the completion of various project components:

### 1. **Packet Filtering Implementation**

The project has successfully implemented packet filtering functionality, allowing users to focus on specific IP addresses and filter out irrelevant traffic. The inclusion of a sample filter, such as `ip.addr == 216.58.213.99 and http`, enables users to pinpoint packets related to a particular IP address and HTTP communication.

### 2. **Detailed Packet Inspection**

Users can now easily inspect individual packets by clicking on them. This includes a thorough examination of both outgoing HTTP request packets and the corresponding incoming HTTP response packets.

### 3. **Packet Stream Tracking Feature**

The project includes a packet stream tracking feature, allowing users to gain a holistic view of the communication between their system and the Google server. By right-clicking on any packet and selecting the follow menu, users can effortlessly track the entire packet stream, enhancing the overall analytical capabilities of the tool.

## Acknowledgments

The successful completion of this project is a result of collaborative efforts, contributions, and feedback from the open-source community. Contributions, bug reports, and suggestions for improvements are highly encouraged to make this tool even more robust and effective in the realm of packet stream analysis.