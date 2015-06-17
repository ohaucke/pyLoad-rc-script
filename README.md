# pyLoad rc Script
[pyLoad](https://github.com/pyload/pyload) rc Script for [FreeBSD](https://www.freebsd.org/)  
German: [pyLoad rc Script für FreeBSD](https://blog.gadean.de/2015/02/pyload-rc-script-fur-freebsd/)

## Parameters
* `pyload_enable` (Default: `NO`)
* `pyload_flags` (Default: `--daemon`)
* `pyload_path` (Default: `/usr/local/etc/${name}`)
* `pyload_pid` (Default: `/var/run/${name}.pid`)
* `pyload_user` (Default: `pyload`)


## Requirements
* [pyLoad](https://github.com/pyload/pyload)
* [FreeBSD](https://www.freebsd.org/)


## Quick install
1. move the `pyload` file into `/usr/local/etc/rc.d/` and set the permissions to `555`  
2. set the specific start parameters in the `rc.conf`  
3. change Shebang in `pyLoadCore.py` to `#!/usr/local/bin/python`  
4. start Service `service pyload start`  


## General
Name: pyload rc Script  
Description:  pyload rc Script for FreeBSD  
Version: 1.0  
Author: Oliver Haucke  
Author URI: https://gadean.de/  
E-Mail: ohaucke@gadean.de  
License: BSD 2-Clause  
License URI: http://opensource.org/licenses/BSD-2-Clause
