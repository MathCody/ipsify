# IPSIFY
Create IPFS links for your github releases.

# Motivation
Github downloads has become slower. We can simply create a symlink of github releases on IPFS network. Then we can get download it from IPFS and it might be faster.

# Desired simple usage
1. Enter a github repo url
2. Download the repo latest release
3. Add it to IPFS
4. Use github release API to update the release with IPFS links*

```
* https://docs.github.com/en/rest/reference/repos#releases
```