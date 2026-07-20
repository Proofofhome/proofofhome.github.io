# Experiment 001: Reviving an Old Laptop

**Status:** 🟡 Initial Block Download (50.66% Complete)
**Last Updated:** July 21, 2026

---

# Experiment Summary

| Item             | Details                                                 |
| ---------------- | ------------------------------------------------------- |
| Experiment       | Reviving an Old Laptop                                  |
| Goal             | Build useful home infrastructure from existing hardware |
| Hardware         | Dell Latitude E7450                                     |
| Operating System | Ubuntu Server 26.04 LTS                                 |
| Software         | Bitcoin Core 31.0                                       |
| Node Type        | Pruned Bitcoin Node                                     |
| Storage Target   | 10 GB prune limit                                       |
| Project Cost     | $0                                                      |
| Status           | Synchronising                                           |

---

## Goal

Can an old laptop become useful sovereign home infrastructure?

The first ProofOfHome experiment explores whether existing hardware can be transformed into a Bitcoin home node using free and open-source software.

Rather than buying new specialised hardware, this experiment documents what can be achieved by repurposing equipment that would otherwise sit unused.

The process will document:

* Setup
* Costs
* Challenges
* Performance
* Power usage
* Lessons learned

---

## Why This Experiment?

Thousands of computers are replaced every year despite still having useful life remaining.

This experiment starts with a simple question:

**Can existing hardware still provide meaningful infrastructure in a modern home?**

Rather than focusing on the newest hardware, ProofOfHome begins by exploring what can be built with what is already available.

---

# Starting Hardware

## Dell Latitude E7450

* Intel Core i5-5300U @ 2.3 GHz
* 8 GB RAM
* 128 GB mSATA SSD
* Battery health: 94%

---

## Photos

![Dell Latitude E7450](../images/genesis/laptopopen.jpg)

![Dell Latitude E7450](../images/genesis/laptopclosed.jpg)

---

# History

This laptop originally ran Windows 7 before being retired.

Instead of becoming electronic waste, it is being given a second life as the first ProofOfHome infrastructure project.

The goal is not to prove old hardware is always better, but to test whether it can still provide useful services with minimal cost.

---

# Current Status

The laptop has successfully been transformed from an old Windows 7 machine into an Ubuntu Server system running Bitcoin Core as a pruned Bitcoin node.

The node is currently performing its **Initial Block Download (IBD)**, downloading and verifying the Bitcoin blockchain before normal operation begins.

## Completed

* Ubuntu Server 26.04 LTS installed
* Dell UEFI boot issues resolved
* Wi-Fi configured
* System updates completed
* Monitoring tools installed
* Bitcoin Core 31.0 installed
* SHA256 checksum verified
* GPG release signature verified
* Pruned node configuration created
* Bitcoin Core daemon started
* Blockchain synchronisation underway

## Next

* Complete blockchain synchronisation
* Record total sync time
* Measure CPU and RAM usage
* Measure power consumption
* Evaluate long-term reliability

---

# Baseline Measurements

## Hardware

* CPU: Intel Core i5-5300U @ 2.3 GHz
* RAM: 8 GB
* Storage: 128 GB mSATA SSD
* Battery health: 94%

## Software

* Ubuntu Server 26.04 LTS
* Bitcoin Core 31.0
* htop
* lm-sensors
* smartmontools

---

# Bitcoin Core Installation

## July 18, 2026

Bitcoin Core was installed using the official Linux binaries.

## Verification

Completed:

* SHA256 checksum verification
* Official GPG release signature verification

## Configuration

* Bitcoin Core version: 31.0
* Operating system: Ubuntu Server 26.04 LTS
* Node type: Pruned node
* Automatic pruning enabled
* Prune target: 10 GB

## Result

Bitcoin Core successfully started and began synchronising with the Bitcoin network.

---

# Synchronisation Progress

## Latest Measurement

**Date:** July 21, 2026

* Network: Bitcoin Mainnet
* Blocks fully validated: **717,597**
* Known block headers: **958,939**
* Verification progress: **50.66%**
* Initial Block Download: **Yes**
* Pruned node: **Enabled**
* Disk usage: **2.07 GB**
* Prune target: **10.48 GB**

## Notes

The node has now validated more than 717,000 blocks and is approximately halfway through the initial blockchain verification process.

Because the node is operating in pruned mode, older block data is automatically removed after validation, allowing the system to operate within the configured storage limit.

---

# Challenges

## Encountered

### Dell UEFI Boot Configuration

The laptop initially required troubleshooting to boot correctly from the Ubuntu Server installer.

### Ubuntu Server Network Configuration

Wi-Fi configuration required troubleshooting due to YAML network configuration issues.

### Initial Blockchain Synchronisation

Running a Bitcoin node on older hardware requires patience. The initial verification process is expected to take significant time.

---

# Timeline

## July 17, 2026

Completed:

* Installed Ubuntu Server 26.04 LTS
* Resolved Dell UEFI USB boot issue
* Configured Wi-Fi
* Installed monitoring tools

---

## July 18, 2026

Completed:

* Downloaded official Bitcoin Core binaries
* Verified SHA256 checksum
* Verified GPG signature
* Installed Bitcoin Core 31.0
* Created pruned node configuration
* Started Bitcoin Core daemon

---

## July 21, 2026

Current progress:

* 717,597 blocks validated
* 50.66% verification complete
* 2.07 GB disk usage
* Running in pruned mode

---

# Costs

| Item                   |     Cost |
| ---------------------- | -------: |
| Dell Latitude E7450    |       $0 |
| Existing charger       |       $0 |
| Kingston USB installer | Existing |
| Ubuntu Server          |       $0 |
| Bitcoin Core           |       $0 |

## Total Cost So Far

**$0**

---

# Metrics To Record

When the experiment is complete:

| Metric                | Result  |
| --------------------- | ------- |
| Total sync time       | Pending |
| Final disk usage      | Pending |
| Average CPU usage     | Pending |
| Peak RAM usage        | Pending |
| Power consumption     | Pending |
| Long-term reliability | Pending |

---

# Lessons Learned

To be completed after the experiment.

Expected observations:

* How capable older hardware remains
* Challenges running infrastructure on consumer devices
* The practicality of pruned Bitcoin nodes
* The importance of documenting the process

---

# Would I Do This Again?

**Pending completion**

Final evaluation will consider:

| Category       | Rating  |
| -------------- | ------- |
| Cost           | Pending |
| Difficulty     | Pending |
| Time Required  | Pending |
| Performance    | Pending |
| Recommendation | Pending |

---

# Results

**Experiment in progress.**

Final results will include:

* Blockchain synchronisation time
* Resource usage
* Power consumption
* Reliability observations
* Overall recommendation
* Lessons for anyone attempting a similar build

---

# Appendix: Commands and Configuration

Commands, configuration files and troubleshooting notes will be documented here to make the experiment reproducible.
