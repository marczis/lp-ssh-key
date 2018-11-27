# Last Pass SSH Key script

Loads and imports ssh keys into Last Pass (https://www.lastpass.com/)

## Prerequirements
  * ssh_keys "folder" in lastpass
  * lpass tool installed & configured (https://github.com/lastpass/lastpass-cli)
    (available in some linux distros as package)
  * ssh-add

## Usage
To load source the script from bash

### ssh_key_load
 * loads one ssh key into the keychain
 * has bash completion (use tab)
 * if no keyname provided lists all of them and you can pick

### ssh_key_import
 * saves an ssh key file into last pass
 * if .pub file exists saves it into the public key field of the SSH key "type"

 ## Contrib
 Please test, pull fix, contact to me and do all the good things.
 As per license, it's all yours for free and I take 0 responsibility.
 
