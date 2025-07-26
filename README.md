# Add-VM Project

## Prerequisites
- **X86-64 Systems**: Install [VirtualBox](https://www.virtualbox.org/).
- Download the VM archive from: [https://assets.01-edu.org/sys](https://assets.01-edu.org/sys).

## Installation Instructions

### For X86-64 (VirtualBox)
1. Download the archive: `01_add-vm.tar.gz` from [https://assets.01-edu.org/sys](https://assets.01-edu.org/sys).
2. Extract the archive to the `VirtualBox VMs` folder in your home directory.
3. In VirtualBox:
   - Go to **Machine** → **Add**.
   - Open the file `01_add-vm.vbox`.
4. The VM should appear in the list as `01_add-vm`.


## Snapshots
A snapshot is a saved state of a VM at a specific time, similar to a backup or version. Snapshots allow you to experiment, make changes, or recover from errors by reverting to the original state.


### Recommended Action
- **Create a Snapshot Immediately**: After importing the VM, create a snapshot to preserve its initial state.
- **How to Revert**: If you need a fresh start, revert to the snapshot or delete the VM and re-import it.

## Verification
To ensure the VM is working:
1. Start the VM.
2. Log in with:
   - **Username**: `root`
   - **Password**: (single space)
3. Stop the VM gracefully to confirm functionality.

