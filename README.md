# Chess Clock Firmware

Published firmware binaries for the chess-clock controller. This repository is
separate from the local source repository and is configured to publish to
`https://github.com/dziadyga/chess-clock-firmware`.

The PlatformIO post-build hook in the source project commits
`firmware/firmware.bin` and `firmware/version.txt` here, then pushes the
`main` branch.
