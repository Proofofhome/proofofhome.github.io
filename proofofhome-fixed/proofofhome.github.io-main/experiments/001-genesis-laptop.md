# Experiment 001: Reviving an Old Laptop

Status: In Progress

## Goal

Can an old laptop become useful sovereign home infrastructure?

The first ProofOfHome experiment explores whether existing hardware can be transformed into a Bitcoin home node.

The process will document the setup, costs, challenges, performance, and lessons learned.

---

## Starting Hardware

Dell Latitude E7450

- Intel Core i5-5300U @ 2.3GHz
- 8GB RAM
- 128GB mSATA SSD
- Battery health: 94%

---

## Photos

![Dell Latitude E7450](../images/genesis/laptopopen.jpg)

![Dell Latitude E7450](../images/genesis/laptopclosed.jpg)

---

## History

This laptop originally ran Windows 7 and is now being repurposed as the first ProofOfHome infrastructure project.

Rather than buying new hardware, this experiment tests what can be achieved by reusing existing equipment.

---

## Current Status

The laptop has been transformed from an old Windows 7 machine into an Ubuntu Server system running Bitcoin Core.

Current phase:

Initial Bitcoin blockchain synchronisation.

Completed:

- Ubuntu Server 26.04 LTS installed
- UEFI boot configuration completed
- Wi-Fi configured
- System updates completed
- Monitoring tools installed
- Bitcoin Core 31.0 installed
- Bitcoin Core download verified using SHA256 checksum
- Bitcoin Core release signature verified using GPG
- Pruned node configuration created
- Bitcoin Core daemon started

Next:

- Monitor blockchain synchronisation
- Record CPU, RAM and storage usage
- Measure performance and power consumption

---

## Baseline Measurements

Initial measurements before Bitcoin node operation.

### Hardware

- CPU: Intel Core i5-5300U @ 2.3GHz
- RAM: 8GB
- Storage: 128GB mSATA SSD
- Battery health: 94%

### Software

- Ubuntu Server 26.04 LTS
- htop installed
- lm-sensors installed
- smartmontools installed

---

## Bitcoin Core Installation

### July 18, 2026

Bitcoin Core was installed using the official Linux binaries.

Verification completed:

- SHA256 checksum verified
- GPG release signature verified

Configuration:

- Bitcoin Core version: 31.0
- Ubuntu Server 26.04 LTS
- Pruned node enabled

Result:

Bitcoin Core daemon successfully started and began initial blockchain synchronisation.

---

## Synchronisation Progress

Latest measurement:

Date: July 2026

- Network: Bitcoin Mainnet
- Current block height: 494,647
- Estimated chain height: 958,696
- Verification progress: 21.96%
- Disk usage: 3.41 GB
- Prune target: 10 GB

Previous measurement:

- Verification progress: 19.7%
- Disk usage: 1.48 GB

Status:

Initial blockchain verification is continuing.

---

## Timeline

### July 2026

Completed:

- ProofOfHome project created
- Genesis hardware selected
- Dell Latitude E7450 documented
- Hardware specifications recorded
- Ubuntu Server installed
- Initial system configuration completed
- Bitcoin Core installed and verified
- Pruned node configured
- Bitcoin Core daemon started

Next:

- Complete blockchain synchronisation
- Record resource usage
- Measure performance and power consumption

---

## Installation Log

### July 17, 2026

Completed:

- Installed Ubuntu Server on Dell Latitude E7450
- Resolved Dell UEFI USB boot issue
- Configured Wi-Fi
- Installed system monitoring tools

### July 18, 2026

Completed:

- Downloaded Bitcoin Core official binaries
- Verified SHA256 checksum
- Verified GPG signature
- Installed Bitcoin Core 31.0
- Created pruned node configuration
- Started Bitcoin Core daemon

---

## Costs

| Item | Cost |
|---|---:|
| Dell Latitude E7450 | $0 |
| Existing charger | $0 |
| Kingston USB installer | Existing |
| Ubuntu Server LTS | $0 |
| Bitcoin Core | $0 |

**Total so far: $0**

---

## Questions

- Can old hardware run useful home infrastructure?
- How much power does it use?
- How reliable is it?
- What problems appear?
- What can be learned?

---

## Results

To be documented.

Future results will include:

- Blockchain synchronisation time
- CPU and RAM usage
- Storage usage
- Power consumption
- Long-term reliability
- Lessons learned
