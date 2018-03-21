# 2018-03-21

## Standup

### Maha

#### Yesterday
* [x] Change Smart conract to define shared with me files
* [x] Move ACL management from Smart contract to IPFS

#### Today

* [ ] Working in front end

### Mahmoud

#### Yesterday

* [x] Fixing: binary blob encryption/decryption
* [x] Updating ACL structure

#### Today

* [ ] ACL management

### Taher

#### Yesterday

* [x] I go deeper in ipfs-api lib to use in storing patient encrypted files/ACL
* [x] Try to solve a issue of how to go from "application/octet-stream" to original file Mimi type(after description).
* [x] starting in design the UX of our app.
* [x] Involve in the issue of how to get private key from MetaMask 

#### Today

* [ ] Continue on the issue of file formats
* [ ] Finalize the UX

---------------------

# 2018-03-20

## Major Updates:

### Improvement: Moving ACLs from ethereum to IPFS

### Issue: Encrypting/Decrypting custom messages:

#### Problem 
No way to encrypt or decrypt data using the user's key, only an [EIP](https://github.com/ethereum/EIPs/issues/130) with almost no progress.

#### Workaround
We will ask the use to provie his own private key for now. (it will never leave the DApp)

---------------------
