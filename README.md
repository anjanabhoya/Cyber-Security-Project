## Network Scan Findings

[cite_start]A network scan was conducted on the `192.168.46.0/24` subnet[cite: 9]. [cite_start]The scan identified a total of **20 active hosts** on the network[cite: 46]. Below is a summary of the key findings for notable devices.

---
### Key Device Analysis

* **Network Gateway (192.168.46.1)**
    * [cite_start]**Device Type:** TP-Link Router [cite: 16]
    * [cite_start]**Open Ports:** `80/tcp` (http), `443/tcp` (https), and `1900/tcp` (upnp)[cite: 16]. These services are likely for the web administration interface and local device discovery.

* **Scanning Machine (192.168.46.116)**
    * [cite_start]**Open Ports:** `135/tcp` (msrpc), `139/tcp` (netbios-ssn), `445/tcp` (microsoft-ds), and `8090/tcp` (opsmessaging)[cite: 46]. The first three are standard Windows networking and file-sharing ports.

* **Mobile Devices (Apple)**
    * [cite_start]Two Apple devices were identified at `192.168.46.3` and `192.168.46.206`[cite: 17, 42].
    * [cite_start]Both devices had ports `49152/tcp` (unknown) and `62078/tcp` (iphone-sync) open[cite: 17, 42].

* **Other Devices**
    * [cite_start]Many devices, such as the one at `192.168.46.10`, were online but showed all scanned ports as closed or in ignored states[cite: 18].
    * [cite_start]Several hosts showed "filtered" ports, such as the device at `192.168.46.252`, indicating that a firewall was likely blocking the scan probes[cite: 45].
