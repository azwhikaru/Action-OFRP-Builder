# 使用 Action 编译 Recovery

- 支持 OrangeFox, TWRP 及其它衍生版本请使用 [Action-TWRP-Builder](https://github.com/azwhikaru/Action-TWRP-Builder)

---

## 致谢
- 所有贡献者

---

## 更新说明
```
= 2023/04/20
- 提交第一个可用版本
```

-----

## 参数说明

| 参数 | 描述                               | 示例 |
| ------------ | -------------------- | ------------ |
| `SYNC_URL` | OrangeFox 提供的同步脚本 | https://gitlab.com/OrangeFox/sync.git |
| `MANIFEST_BRANCH` | 源码分支 | 12.1                                                         |
| `DEVICE_TREE_URL` | Device tree URL | https://github.com/OrangeFoxRecovery/device_xiaomi_laurel_sprout |
| `DEVICE_TREE_BRANCH` | Device tree 分支 | fox_12.1 |
| `DEVICE_PATH` | Device tree 位置 | device/xiaomi/laurel_sprout |
| `COMMON_TREE_URL` | Common tree URL |  |
| `COMMON_PATH` | Common tree 位置 |  |
| `DEVICE_NAME` | 机型 | laurel_sprout |
| `MAKEFILE_NAME` | Makefile 名称 | twrp_laurel_sprout |
| `BUILD_TARGET` | 编译目标(boot/recovery/vendorboot) | recovery |

-----

## 如何使用
```
例如你的 Github 用户名是 "JohnSmith"
```
#### 1. 点击当前仓库右上角的 "Fork" 按钮
![image](https://user-images.githubusercontent.com/37921907/177914706-c92476c5-7e14-4fb3-be94-0c8a11dae874.png)
#### 2. 等待自动重定向后，你将会看到你的用户名
![image](https://user-images.githubusercontent.com/37921907/177915106-5bde6fc9-303c-479e-b290-22b48efd1e4e.png)
-----

## 开始编译 Recovery
#### 9. 进入 "Actions-Recovery Build"
![image](https://user-images.githubusercontent.com/37921907/177915304-8731ed80-1d49-48c9-9848-70d0ac8f2720.png)
#### 10. 点击 "Run workflow" 并按照参数说明内的描述填写参数
![image](https://user-images.githubusercontent.com/37921907/177915346-71c29149-78fb-4a00-996f-5d84ffc9eb8c.png)
#### 11. 填写完毕后, 点击 "Run workflow" 开始运行

-----

## 编译结果
可以在 [Release](../../releases) 下载

文件没有被上传到 Release？请检查步骤 "Check the output directory before uploading" 并检查文件名