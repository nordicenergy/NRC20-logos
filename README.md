# NRC20-logos
Repository to store NRC20 token logos
* The NRC20 token logos will be used by several clients such as Nordic Energy block explorer when displaying the infomations of NRC20.


## Steps to add your NRC20 logo
* Fork this repository
* Add your logo by creating the logo image name using your NRC20 contract net-address and placing it inside `NRC20/`, e.g. `NRC20/net1pdv9lrdwl0rg5vglh4xtyrv3wjk3wsqket7zxy.png`
* Append your NRC20 token's basic information (including address, name, symbol, decimals, totalSupply, description, website) to the bottom of the list.json,

For example, append yours to the last lines of [list.json](https://github.com/nordicenergy/NRC20-logos/blob/master/list.json)

```
[
...
{
    "address": "net10y76c0kyj6d9hmngf0859yx49l4c75d5z77zxr",
    "name": "SEED",
    "symbol": "SEED",
    "decimals": 6,
    "totalSupply": "201925001200",
    "website": "https://nordicenergy.io",
    "description": {
        "en": "..."
    }
}
]
```

* Create a PR
* Once the Nordic Energy team approves your logo, it will be consumed by clients like Harmony block explorer


## Image Requirements
- dimension: `256px by 256px` or `512px by 512px`
- size: up to `100 KB`. TIP: use free drag and drop online service [tinypng](https://tinypng.com/) to optimize image size
