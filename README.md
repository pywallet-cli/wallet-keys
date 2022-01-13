# Extract Bitcoin Private Keys from wallet.dat (CLI)
[![PyPI version](https://badge.fury.io/py/bip-utils.svg)](https://badge.fury.io/py/bip-utils)
[![Build Status](https://travis-ci.com/ebellocchia/bip_utils.svg?branch=master)](https://travis-ci.com/ebellocchia/bip_utils)
[![codecov](https://codecov.io/gh/ebellocchia/bip_utils/branch/master/graph/badge.svg)](https://codecov.io/gh/ebellocchia/bip_utils)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/9a0c9c6a3d6444fab91f58fe8ec9e35c)](https://www.codacy.com/gh/ebellocchia/bip_utils/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=ebellocchia/bip_utils&amp;utm_campaign=Badge_Grade)
[![CodeFactor](https://www.codefactor.io/repository/github/ebellocchia/bip_utils/badge)](https://www.codefactor.io/repository/github/ebellocchia/bip_utils)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://raw.githubusercontent.com/ebellocchia/bip_utils/master/LICENSE)

Dumps private keys from unencrypted wallet.dat files using the "0201010420" private key marker.

Searches through a given file looking for the "0201010420" byte marker, then extracts the next 32 bytes. Converts the hex to both Compressed and Uncompressed WIFs and dumps to STDOUT (along with matching address to making searching easier)


This script can NOT be used with wallet.dat's that have been encrypted but it works with wallet.dat corrupted

# Linux Usage
    Put your wallet.dat in the same directory and execute:
    sudo ./keys-cli

# Windows Usage
    Put your wallet.dat in the same directory and execute:
    Execute keys.exe in CLI (cmd.exe)

## Donation ##
If you find this program helpful, please consider a donation:

BTC: bc1qqtspvvyl5nv2dwffd0zwppledlmct7sydpd9l5

**Thank You!**
