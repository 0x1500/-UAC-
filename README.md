# 软件屏蔽器


阻止指定软件的管理员授权, 无需后台运行.

项目灵感来源: [Windows apps that amaze us](https://amazing-apps.gitbook.io/windows-apps-that-amaze-us/zh-cn/blacklist).

## 下载



> [!Note]
> 有两种可供选择的版本, `mwp.bundled.zip` 是单文件程序, 但容易被杀毒软件报毒; `mwp.unbundled.zip` 是证书和程序分离的包.

## 命令行参数

- 无参数 : 启动图形界面.
- `--silent-update` : 在后台进行更新. (仅单文件版可用)
- `--disallow-all` : 屏蔽所有支持的软件.
- `--allow-all` : 允许所有支持的软件.
- `--remove` : 清理更新的缓存文件.
- `--allow`: (从"打开文件"对话框)选择并允许程序.

> 程序必须拥有数字签名,因为本功能使用其数字签名实现,下同

- `--disallow`: 选择并屏蔽程序.
- `--allow=file`: 允许传入的 `file`.
- `--disallow=file`: 屏蔽传入的 `file`.

## 系统支持

需要 .NET Framework 4.7.2

- Windows 10
- Windows 8.1
- Windows 7

## 语言支持

- 简体中文
- English

## 例子

### 屏蔽并保存

<img height="250" alt="屏蔽并保存" src="./assets/disallow.png">

### 屏蔽后

<img height="250" alt="屏蔽后" src="./assets/after.png">
