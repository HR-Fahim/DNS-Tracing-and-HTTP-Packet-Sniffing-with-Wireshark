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

## Collaborative Contribution

This project invites contributions from individuals keen on exploring the dynamics of network analysis and DNS packet dissection. Whether you choose to explore, share insights, or enhance the project, your participation contributes to a richer understanding of DNS communication during routine web-surfing.
