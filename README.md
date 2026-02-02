# RTSS Chinese Skin and Localization

## 仓库介绍

本仓库提供了 RivaTuner Statistics Server (RTSS) 的中文本地化包和中文皮肤，使RTSS界面更加符合中文用户的使用习惯。

## 兼容版本
RTSS 中文本地化包和皮肤已测试兼容以下版本的 RTSS：

- RTSS 7.3.7 及以上版本

## 目录结构

- **Localization/CHS/**: 包含RTSS的中文本地化文件
- **Skin/chinese/**: 包含RTSS的中文皮肤文件

## 汉化包使用方法

1. 下载本仓库的文件
2. 找到RTSS的安装目录（通常为 `C:\Program Files (x86)\RivaTuner Statistics Server`）
3. 将 `Localization/CHS/` 目录复制到RTSS安装目录下的 `Localization/` 文件夹中
4. 启动RTSS，在设置中选择中文语言

## 皮肤使用方法

1. 下载本仓库的文件
2. 找到RTSS的安装目录
3. 将 `Skin/chinese/` 目录复制到RTSS安装目录下的 `Skin/` 文件夹中
4. 打开终端编译皮肤
   - 导航到 `C:\Program Files (x86)\RivaTuner Statistics Server` 目录
   - 执行 `.\RTSS.exe -cs chinese`
5. 启动RTSS，在设置中选择中文皮肤

### 或者
1. 下载本仓库的文件
2. 找到RTSS的安装目录
3. 将 `chinese.usf` 目录复制到RTSS安装目录下的 `Skin/` 文件夹中
4. 启动RTSS，在设置中选择中文皮肤

## 注意事项

- 确保您使用的是兼容版本的RTSS
- 操作前建议备份原有的本地化和皮肤文件
- 若遇到问题，可恢复原有的文件
- 皮肤基于RTSS默认皮肤修改，可能与未来版本的RTSS不兼容