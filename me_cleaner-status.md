# Current status of me_cleaner
Please let me know [here](https://github.com/corna/me_cleaner/issues/3) if me_cleaner works on your device (even if it is already listed as working)

| PCH               | CPU               | ME   | SKU      | Status    |
|:-----------------:|:-----------------:|:----:|:--------:|:---------:|
|                   |                   | 1.x-5.x |       | **WORKS** * |
| Ibex Peak         | Nehalem/Westmere  | 6.0  | Ignition | **WORKS** |
| Ibex Peak         | Nehalem/Westmere  | 6.x  | 1.5/5 MB | **WORKS** |
| Cougar Point      | Sandy Bridge      | 7.x  | 1.5/5 MB | **WORKS** |
| Panther Point     | Ivy Bridge        | 8.x  | 1.5/5 MB | **WORKS** |
| Lynx/Wildcat Point| Haswell/Broadwell | 9.x  | 1.5/5 MB | **WORKS** |
| Wildcat  Point LP | Broadwell Mobile	| 10.0 | 1.5/5 MB | **WORKS** |
| Sunrise Point     | Skylake/Kabylake	| 11.x | CON/COR  | **WORKS** |
| Union Point       | Kabylake	        | 11.x | CON/COR  | **WORKS** |
| 300-series        | Coffee Lake       | 11.x | CON/COR  | UNTESTED  |

\* Firmware fully removed

| SoC                   | TXE | SKU             | Status       |
|:---------------------:|:---:|:---------------:|:------------:|
| Bay Trail             | 1.x | 1.25/1.375/3 MB | UNTESTED     |
| Braswell/Cherry Trail | 2.x | 1.375 MB        | **WORKS**    |

Currently me_cleaner works partially on platforms with Intel Boot Guard set in Verified (+ Measured) Boot. Read [this](https://github.com/corna/me_cleaner/wiki/Intel-Boot-Guard) to learn more about Intel Boot Guard and its implications about _me_cleaner_.