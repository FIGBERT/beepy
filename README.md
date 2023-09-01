# Beepy CLI
Your one-stop-shop for all things Beepy, as long as all things means:
going from zero to messaging with Beeper on your device, or copying logs
from your Beepy to your computer (actually that second bit is coming
soon).

## Download
You can find the latest binaries precompiled in [GitHub Actions]. If
you're on Linux, you're done! If you on macOS, make sure to run `brew
install libolm` before running.

Alternatively, you can build it yourself by cloning the repo and running
`go build .`. Building requires Go 1.20 or higher, and a `libolm`
installation.

`beepycli` supports x86_64 and arm64 on Linux and macOS, and arm7 on Linux.
Windows is not supported natively, please use WSL.

## Usage
To log in to your Beeper account and install `gomuks`—the Beeper client
for Beepy—all you have to do is run `beepycli`.

To copy logs from your Beepy device to your laptop, run `beepycli
--logs`. Once that works, that is.

~~Made in collaboration with Shadow Wizard Money Gang.~~

[GitHub Actions]: https://github.com/beeper/beepycli/actions
