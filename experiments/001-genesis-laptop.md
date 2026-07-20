# Experiment 001: Reviving an Old Laptop

**Status:** 🟡 Initial Block Download (50.66% Complete)

---

## Goal

Can an old laptop become useful sovereign home infrastructure?

The first ProofOfHome experiment explores whether existing hardware can be transformed into a Bitcoin home node using free and open-source software.

Rather than purchasing specialised hardware, this experiment documents what can be achieved by repurposing equipment that would otherwise sit unused.

Throughout the experiment I'll document the setup process, costs, challenges, performance, resource usage and lessons learned.

---

## Starting Hardware

**Dell Latitude E7450**

* Intel Core i5-5300U @ 2.3 GHz
* 8 GB RAM
* 128 GB mSATA SSD
* Battery health: 94%

---

## Photos

![Dell Latitude E7450](../images/genesis/laptopopen.jpg)

![Dell Latitude E7450](../images/genesis/laptopclosed.jpg)

---

## History

This laptop originally ran Windows 7 before being retired.

Instead of becoming electronic waste, it is being given a second life as the first ProofOfHome infrastructure project.

The aim is to demonstrate that useful home infrastructure doesn't always require new hardware—sometimes the best place to start is with what you already own.

---

## Current Status

The laptop has successfully been transformed from an ageing Windows 7 machine into an Ubuntu Server system running Bitcoin Core as a pruned node.

The node is currently performing its **Initial Block Download (IBD)**, downloading and verifying the Bitcoin blockchain before entering normal operation.

### Completed

* Ubuntu Server 26.04 LTS installed
* UEFI boot configuration completed
* Wi-Fi configured
* System updated
* Monitoring tools installed
* Bitcoin Core 31.0 installed
* SHA256 checksum verified
* GPG release signature verified
* Pruned node configured
* Bitcoin Core daemon started
* Blockchain synchronisation in progress

### Next

* Complete blockchain synchronisation
* Record total synchronisation time
* Measure CPU, RAM and storage usage
* Measure power consumption
* Evaluate long-term performance

---

## Baseline Measurements

### Hardware

* CPU: Intel Core i5-5300U @ 2.3 GHz
* RAM: 8 GB
* Storage: 128 GB mSATA SSD
* Battery health: 94%

### Software

* Ubuntu Server 26.04 LTS
* Bitcoin Core 31.0
* htop
* lm-sensors
* smartmontools

---

## Bitcoin Core Installation

### July 18, 2026

Bitcoin Core was installed using the official Linux binaries.

### Verification

* SHA256 checksum verified
* Official GPG release signature verified

### Configuration

* Bitcoin Core 31.0
* Ubuntu Server 26.04 LTS
* Pruned node enabled
* Automatic pruning (10 GB target)

### Result

Bitcoin Core successfully started and began synchronising with the Bitcoin network.

---

## Synchronisation Progress

### Latest Measurement

**Date:** July 2026

* Network: Bitcoin Mainnet
* Blocks fully validated: **717,597**
* Known block headers: **958,939**
* Verification progress: **50.66%**
* Initial Block Download: **Yes**
* Pruned node: **Enabled**
* Prune target: **10 GB**
* Disk usage: **2.07 GB**

### Notes

The node has now validated more than **717,000 blocks** and is approximately halfway through the initial blockchain verification process.

Because the node is operating in pruned mode, older block data is automatically removed after verification, allowing the node to operate comfortably within the configured 10 GB storage limit.

Synchronisation continues to progress steadily on the Dell Latitude E7450.

---

## Timeline

### July 2026

### Completed

* ProofOfHome project created
* Dell Latitude E7450 selected
* Hardware documented
* Ubuntu Server installed
* Dell UEFI boot issues resolved
* Wi-Fi configured
* Bitcoin Core downloaded
* SHA256 checksum verified
* GPG signature verified
* Bitcoin Core 31.0 installed
* Pruned node configured
* Bitcoin daemon started
* Initial blockchain synchronisation reached **50.66%**

### Next

* Complete blockchain synchronisation
* Record total synchronisation time
* Measure CPU, RAM and storage usage
* Measure power consumption
* Publish final experiment results

---

## Installation Log

### July 17, 2026

* Installed Ubuntu Server 26.04 LTS
* Resolved Dell UEFI USB boot issue
* Configured Wi-Fi
* Installed system monitoring tools

### July 18, 2026

* Downloaded official Bitcoin Core binaries
* Verified SHA256 checksum
* Verified GPG signature
* Installed Bitcoin Core 31.0
* Created pruned node configuration
* Started Bitcoin Core daemon

### Current

Bitcoin Core continues synchronising with the Bitcoin network.

Current progress:

* 717,597 blocks validated
* 50.66% verification complete
* Approximately 2.07 GB of disk space in use
* Running in pruned mode with a 10 GB storage target

---

## Costs

| Item                    |     Cost |
| ----------------------- | -------: |
| Dell Latitude E7450     |       $0 |
| Existing charger        |       $0 |
| Kingston USB installer  | Existing |
| Ubuntu Server 26.04 LTS |       $0 |
| Bitcoin Core            |       $0 |

**Total project cost so far: $0**

---

## Questions

This experiment aims to answer several practical questions:

* Can decade-old hardware run useful home infrastructure?
* How long does a Bitcoin node take to synchronise on older hardware?
* How much power does it consume?
* How much storage is actually required when running a pruned node?
* What challenges arise during setup?
* Is repurposing old hardware a practical alternative to buying new equipment?

---

## Results

*Experiment still in progress.*

The final report will include:

* Total blockchain synchronisation time
* CPU usage
* RAM usage
* Final storage usage
* Power consumption
* Overall performance
* Reliability observations
* Lessons learned
* Recommendations for anyone attempting the same build
