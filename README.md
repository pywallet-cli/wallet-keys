# Mnemonic Validator (CLI)
    Dumps private keys from unencrypted wallet.dat files using the "0201010420" private key marker.
    Searches through a given file looking for the "0201010420" byte marker, then extracts the next 32 bytes. Converts the hex to both Compressed and Uncompressed WIFs and dumps to STDOUT (along with matching address to making searching easier)

    This script can NOT be used with wallet.dat's that have been encrypted.

# Linux Usage
    Put your wallet.dat in the same directory and execute:
    sudo ./keys-cli

# Windows Usage
    Put your wallet.dat in the same directory and execute:
    Execute keys.exe in CLI (cmd.exe)

