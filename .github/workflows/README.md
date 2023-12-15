# Github Actions for Awful.apk

## Testing Locally

### MacOS ARM-based machines
You may need to run `act` with the flag `--container-architecture linux/amd64` or risk compatibility issues.

The main error seems to be `rosetta error: failed to open elf at /lib64/ld-linux-x86-64.so.2`