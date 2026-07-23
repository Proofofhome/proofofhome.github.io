# Experiment 001: Reviving an Old Laptop

**Status:** 🟡 Initial Block Download (**71.78% Complete**)
**Last Updated:** July 23, 2026

...

# Current Status

The laptop has successfully been transformed from an ageing Windows 7 machine into an Ubuntu Server system running Bitcoin Core as a pruned Bitcoin node.

The node is currently performing its **Initial Block Download (IBD)**, downloading and verifying the Bitcoin blockchain before entering normal operation.

## Completed

* Ubuntu Server 26.04 LTS installed
* Dell UEFI boot issues resolved
* Wi-Fi configured
* System updated
* Monitoring tools installed
* Bitcoin Core 31.0 installed
* SHA256 checksum verified
* GPG release signature verified
* Pruned node configured
* Bitcoin Core daemon started
* Blockchain synchronisation reached **71.78%**

## Next

* Complete blockchain synchronisation
* Record total synchronisation time
* Measure CPU and RAM usage
* Measure power consumption
* Evaluate long-term reliability
* Publish final experiment results

---

# Synchronisation Progress

The node is currently performing its **Initial Block Download (IBD)**. The checkpoints below document progress over time while running on the Dell Latitude E7450.

| Date      | Verification | Blocks Validated | Disk Usage | Notes                                                                                                                      |
| --------- | -----------: | ---------------: | ---------: | -------------------------------------------------------------------------------------------------------------------------- |
| July 2026 |       21.96% |          494,647 |    3.41 GB | Initial synchronisation after Bitcoin Core installation.                                                                   |
| July 2026 |       50.66% |          717,597 |    2.07 GB | Approximately halfway through blockchain verification. Pruning operating as expected.                                      |
| July 2026 |       71.78% |         838,773+ |    4.09 GB | Synchronisation continues steadily. Automatic pruning reclaimed storage while remaining below the configured 10 GB target. |

## Latest Update

The node has now verified **more than 71%** of the Bitcoin blockchain and continues to synchronise without issue.

One interesting observation during this stage is how **pruning dynamically manages storage**. As older validated blocks become unnecessary, Bitcoin Core automatically removes them to remain within the configured storage target.

During the latest synchronisation checkpoint, disk usage dropped from approximately **8.6 GB** to **4.09 GB** while the prune height advanced from **834,426** to **838,773**, demonstrating that a fully validating Bitcoin node can comfortably operate within a relatively small storage allocation when running in pruned mode.

The experiment remains in the **Initial Block Download** phase and is expected to continue until the blockchain has been fully verified.

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

Milestone reached:

* 717,597 blocks validated
* 50.66% verification complete
* 2.07 GB disk usage
* Initial Block Download continuing

---

## July 23, 2026

Milestone reached:

* Verification progress increased to **71.78%**
* More than **838,000 blocks** validated
* Automatic pruning continued to reclaim storage
* Disk usage remained well below the configured 10 GB limit
* Initial Block Download continuing

---

# Metrics To Record

When the experiment is complete:

| Metric                     | Result  |
| -------------------------- | ------- |
| Total synchronisation time | Pending |
| Final blockchain height    | Pending |
| Final disk usage           | Pending |
| Average CPU usage          | Pending |
| Peak RAM usage             | Pending |
| Power consumption          | Pending |
| Long-term reliability      | Pending |
| Total project cost         | $0      |

---

# Results

**Experiment still in progress.**

The final report will include:

* Total blockchain synchronisation time
* CPU and RAM utilisation
* Final storage usage
* Power consumption
* Long-term reliability observations
* Overall recommendation
* Lessons learned
* Whether a decade-old laptop remains a practical platform for home Bitcoin infrastructure
