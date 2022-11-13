# Tools Used
- [Nuclei](https://github.com/projectdiscovery/nuclei)
- [Feroxbuster](https://www.kali.org/tools/feroxbuster/)


# URLs Found 
- https://scan.snapchat.com/static
- https://scan.snapchat.com/Static/types/utils

# Source Code Messages 
>  ERROR ITEM CONTAINER (removed during loading to avoid bug 39098) 


# Results 
> WLD      GET        1l     1644w    59328c Got 200 for https://scan.snapchat.com/fdf4de9cba8e4bfebbe1d615bdd05bbe (url length: 32)
WLD      GET        1l     1644w    59328c Got 200 for https://scan.snapchat.com>  51e54d695b3d468ba04c04ba7ffa2b090c3a74d023a24fe3a3194d9648f9c6ddc3b3ed0a704e4939869ddb2c628c0765 (url length: 96)
301      GET       10l       16w      179c https://scan.snapchat.com/static => /static/
301      GET       10l       16w      179c https://scan.snapchat.com/Static => /Static/
301      GET       10l       16w      191c https://scan.snapchat.com/static/types => /static/types/
301      GET       10l       16w      213c https://scan.snapchat.com/static/types/components => /static/types/components/
301      GET       10l       16w      203c https://scan.snapchat.com/static/types/utils => /static/types/utils/
301      GET       10l       16w      191c https://scan.snapchat.com/Static/types => /Static/types/
301      GET       10l       16w      213c https://scan.snapchat.com/Static/types/components => /Static/types/components/
301      GET       10l       16w      203c https://scan.snapchat.com/Static/types/utils => /Static/types/utils/
[####################] - 23m   270000/270000  0s      found:10      errors:168500 
[####################] - 11m    30002/30000   43/s    https://scan.snapchat.com/ 
[####################] - 11m    30000/30000   43/s    https://scan.snapchat.com/static 
[####################] - 9m     30000/30000   50/s    https://scan.snapchat.com/Static 
[####################] - 6m     30000/30000   77/s    https://scan.snapchat.com/static/types 
[####################] - 13m    30000/30000   36/s    https://scan.snapchat.com/static/types/components 
[####################] - 5m     30000/30000   83/s    https://scan.snapchat.com/static/types/utils 
[####################] - 14m    30000/30000   34/s    https://scan.snapchat.com/Static/types 
[####################] - 15m    30000/30000   32/s    https://scan.snapchat.com/Static/types/components 
[####################] - 10m    30000/30000   47/s    https://scan.snapchat.com/Static/types/utils 
