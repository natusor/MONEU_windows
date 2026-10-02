# MONEU binaries for Windows

Prebuilt node for Windows 10 and 11, 64-bit. No libraries to install.

## Download and run

Unpack moneu-0.2.2-windows-x86_64.zip, open the MONEU-windows folder
and run moneu.exe.

The rest is in README.txt inside the archive.

## Check what you downloaded

    sha256sum -c SHA256SUMS

On Windows, in PowerShell:

    Get-FileHash moneu-0.2.2-windows-x86_64.zip -Algorithm SHA256

The hash must match the one in SHA256SUMS.

## Check who built it

    gpg --import moneu-binary-releases-key.asc
    gpg --verify moneu-0.2.2-windows-x86_64.zip.asc moneu-0.2.2-windows-x86_64.zip

It should say:

    Good signature from "natusor (MONEU binary releases signing)"

The key fingerprint is:

    9B3E AC79 B47A A748 AFA2  DE54 62ED 724E 57AF 49D9

Source code: https://github.com/natusor/MONEU
Website: https://moneu.cc
