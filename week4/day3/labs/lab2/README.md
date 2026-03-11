What I Did
Created an Availability Set named Linux-AvailSet-duyghu with 2 Fault Domains and 5 Update Domains.
Deployed two Linux VMs: LinuxVM-01-duyghu assigned to Fault Domain 0 and Update Domain 0, linux-vm-2-duyghu assigned to Fault Domain 1 and Update Domain 1.
Verified both VMs appear in the Availability Set and captured a screenshot showing their fault and update domain assignments.
How Fault Domains and Update Domains Help High Availability
Fault Domains protect VMs from hardware failures by placing them in separate racks.
Update Domains ensure VMs are updated one at a time during maintenance to prevent downtime.
With multiple VMs, Azure distributes them across the available fault and update domains to maximize uptime.
