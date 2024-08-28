# Off The Grid Interactions Fix

Certain interactions on tablets or the Get Famous drones check for the
Off-The-Grid lot trait instead of checking for what utilities are currently
enabled. There are bugs filed for this, but no resolution has come:

* [[NEEDS INPUT] Off Grid Living: Internet doesn't work for Slablet despite Power](https://answers.ea.com/t5/Bug-Reports/NEEDS-INPUT-Off-Grid-Living-Internet-doesn-t-work-for-Slablet/td-p/9370963)
* [[NEEDS INPUT] [GF] Drone will not stream in powered Off the Grid lot](https://answers.ea.com/t5/Bug-Reports/NEEDS-INPUT-GF-Drone-will-not-stream-in-powered-Off-the-Grid-lot/td-p/9185507)

This mod fixes the affected interactions by changing them to use `utility_info`
instead of checking for the lot trait.
