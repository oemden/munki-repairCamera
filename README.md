# Repair Camera

We had trouble on a computer with a camera randomly not working.

The script simply kills bugged process and the camera comes back. 

Used in a munki .nopkg on demand script.

### munkiimport example

```
makepkginfo --nopkg --name=RepairCamera --pkgvers=0.1 \
--postinstall_script=/path/to/RepairCamera.sh > RepairCamera.pkginfo
```


> Note: Tested on 10.14.x, should work on others macOs.
