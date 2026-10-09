# OrangeFox Action Builder
Compile your first custom recovery from OrangeFox Recovery using Github Action.

# How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > `OrangeFox - Build` > `Run workflow`, then fill all the required information:
 * MANIFEST_BRANCH (`16.0`, `14.1` and `12.1`)
 * DEVICE_TREE (Your device tree repository link.)
 * DEVICE_TREE_BRANCH (Your device tree repository branch.)
 * DEVICE_PATH (`device/vendor/codename`)
 * DEVICE_NAME (Your device codename)
 * BUILD_TARGET (`boot`, `recovery`, `vendorboot`)

 # Note
* This action supports manifests 16.0, 14.1 (*EXPERIMENTAL* upstream) and 12.1. 11.0 and below are obsolete (upstream R11.2 dropped 11.0).
* Make sure your tree uses the right variables for the matching manifest from the OrangeFox build vars doc, to avoid build errors.
