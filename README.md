# FIDO2Signing
Examples of code signing with FIDO2 tokens

## This change was made using a signed commit.

This change wasn't signed.

Signed again!

## Signing commits in WSL
In order to sign commits in WSL:

1. Make sure Win32-OpenSSH is installed properly
2. Configure the `SSH_SK_HELPER` environment variable within the WSL session to point to the `ssh_sk_helper.exe` from Win32-OpenSSH, for example: `export SSH_SK_HELPER="/mnt/c/Program Files/OpenSSH/ssh-sk-helper.exe"`  
3. Ensure that the signing key and allowed signers files are set to correct paths in WSL.
4. Make sure your identity, key format and public key are in the allowed signers file

