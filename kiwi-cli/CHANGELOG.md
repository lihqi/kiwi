# 🐤 Change Log

Kiwi Cli

## 1.0.22 (2022-03-04)
-  kiwi --extract 修复多文件提取时的并发问题
-  kiwi --extract 修复文案key出现undefined的情况
## 1.0.21 (2022-03-01)
-  kiwi --extract 添加 --prefix 参数，自定义配置 118N 提取文案路径
## 1.0.20（2022-02-28）
- kiwi 优化在vue环境下中文检测与linter保持同步
## 1.0.19（2022-01-26）

### Breaking changes

- kiwi --extract 添加百度和拼音翻译源，且支持批量文件以,分隔符输入（原本仅支持指定文件夹）
- 配置文件 kiwi-config.json 添加 defaultTranslateKeyApi

## 1.0.18（2021-12-07）

### Breaking changes

- 配置文件 kiwi-config.json 移动至根目录下
