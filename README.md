DebugEnhancer
=============

[![Build Status](https://github.com/devicemanager/DebugEnhancer/workflows/CI/badge.svg?branch=master)](https://github.com/devicemanager/DebugEnhancer/actions) [![Scan Status](https://scan.coverity.com/projects/22205/badge.svg?flat=1)](https://scan.coverity.com/projects/22205)

A Lilu plugin intended to enable debug output in the macOS kernel,
the original idea belongs to Piker-Alpha, see https://github.com/Piker-Alpha/debugMachKernel.sh for more details.

#### Boot-args
- `-dbgenhdbg`   turns on debugging output
- `-dbgenhbeta`  enables loading on unsupported osx
- `-dbgenhoff`   disables kext loading
- `-dbgenhiolog` redirect IOLog output to kernel vprintf (the same as for kdb_printf and kprintf)
