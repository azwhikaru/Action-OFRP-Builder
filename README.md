# Build Recovery using Github Actions

- Support OrangeFox, [TWRP](https://github.com/azwhikaru/Action-TWRP-Builder) is here
- [中文说明](./README_CN.md)

---

## Thanks to
- All contributors

---

## Release Notes
```
= 2023/04/20
- The first available version is submitted.
```

-----

## Parameter Description

| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `SYNC_URL` | Script specified by OrangeFox | https://gitlab.com/OrangeFox/sync.git |
| `MANIFEST_BRANCH` | Source branch | 12.1                                                         |
| `DEVICE_TREE_URL` | Device address | https://github.com/OrangeFoxRecovery/device_xiaomi_laurel_sprout |
| `DEVICE_TREE_BRANCH` | Device branch | fox_12.1 |
| `DEVICE_PATH` | Device location | device/xiaomi/laurel_sprout |
| `COMMON_TREE_URL` | Common tree address |  |
| `COMMON_PATH` | Common tree location |  |
| `DEVICE_NAME` | Model name | laurel_sprout |
| `MAKEFILE_NAME` | Makefile name | twrp_laurel_sprout |
| `BUILD_TARGET` | Build Target Partition (boot/recovery/vendorboot) | recovery |

-----

## How to use
```
For example, your username is: JohnSmith
```
#### 1. Click 'Fork' in the upper right corner of this repository
![image](https://user-images.githubusercontent.com/37921907/177914706-c92476c5-7e14-4fb3-be94-0c8a11dae874.png)
#### 2. After waiting for the automatic redirection, you will see your own username
![image](https://user-images.githubusercontent.com/37921907/177915106-5bde6fc9-303c-479e-b290-22b48efd1e4e.png)
-----

## Building the Recovery
#### 9. Click 'Actions-Recovery Build'
![image](https://user-images.githubusercontent.com/37921907/177915304-8731ed80-1d49-48c9-9848-70d0ac8f2720.png)
#### 10. Click 'Run workflow' and fill in according to the above 'parameter description'
![image](https://user-images.githubusercontent.com/37921907/177915346-71c29149-78fb-4a00-996f-5d84ffc9eb8c.png)
#### 11. After filling in, click 'Run workflow' to start running

-----

## Compilation results
Can be downloaded at [Release](../../releases)

File not being uploaded to Release? Please check the step 'Check the output directory before uploading' and check the file name