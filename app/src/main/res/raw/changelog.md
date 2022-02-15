# alpha更新日志

## Magisk (b1faa5ee-alpha)
- [App] 支持SharedUserId
- [App] 还原boot镜像后删除备份文件
- [App] 内置当前版本更新日志
- [General] 不再自动解锁设备块
- [App] 适配 Android 12L
- [App] 添加崩溃统计
- [App] 允许加载zygisk模块
- [General] 签名验证

### 如何安装？
通过Magisk应用来安装和卸载Magisk，一般情况应直接在应用内完成，第一次安装等特殊情况应修补镜像后使用fastboot/odin工具刷入。
通过自定义Recovery不是受支持的方式。

# 上游更新日志

## Magisk (3dc7d77e) (24304)

Fixed several compatibility issues with `magiskinit`

## Diffs to v24.3

- [MagiskInit] Update 2SI implementation, significantly increase device compatibility (e.g. Sony Xperia devices)
- [MagiskInit] Introduce new `sepolicy` injection mechanism
