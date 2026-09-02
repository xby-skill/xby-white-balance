# xby-white-balance

DeepSeek Harness (DSH) 的插件：白平衡

输入偏色或偏温图片，自动校正白平衡还原中性灰与真实色彩，去除偏冷或偏暖色偏，适用于照片调色、产品拍摄、监控与实景记录等场景。返回JSON格式数据，包含结果图片下载链接。

## 功能

- **set_xby_apikey** — 在聊天中设置 API 密钥（自动持久化，重启有效）
- **white_balance** — 输入偏色或偏温图片，自动校正白平衡还原中性灰与真实色彩，去除偏冷或偏暖色偏，适用于照片调色、产品拍摄、监控与实景记录等场景。返回JSON格式数据，包含结果图片下载链接。 需要输入图片文件链接。
- **white_balance_for_data_base64** — 输入偏色或偏温图片，自动校正白平衡还原中性灰与真实色彩，去除偏冷或偏暖色偏，适用于照片调色、产品拍摄、监控与实景记录等场景。返回JSON格式数据，包含结果图片下载链接。 需要输入图片文件的BASE64编码。
- **white_balance_for_data_file** — 输入偏色或偏温图片，自动校正白平衡还原中性灰与真实色彩，去除偏冷或偏暖色偏，适用于照片调色、产品拍摄、监控与实景记录等场景。返回JSON格式数据，包含结果图片下载链接。 需要输入图片文件的文件路径。

## 安装

### 方式一：从 GitHub 直接安装（推荐）

```bash
# 格式: dsh plugin --profile <profile> add github:<owner>/<repo>
dsh plugin --profile web add github:xby_skill/xby-white-balance
```

### 方式二：从本地目录安装（开发模式）

```bash
# 仅用于本地开发调试
dsh plugin --profile web add /absolute/path/to/xby-white-balance
```

### 方式三：通过 cordis.patch.yml 开发调试

```bash
dsh web --profile web --patch /absolute/path/to/dsh-ocr-plugin/cordis.patch.yml
```



## 配置

### 获取 API 密钥

前往 [小笨羊官网](https://xiaobenyang.com) 注册并获取 API 密钥。
