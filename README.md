# Windows Dotfile

## Nushell

- Nushell 中使用 Oh My Posh 的文档见（内容有些落后）：  
  <https://www.nushell.sh/book/3rdpartyprompts.html#oh-my-posh>
- `.poshthemes/`: Oh My Posh 主题存放目录。
- oh-my-posh 在 [v26.0.0](https://github.com/JanDeDobbeleer/oh-my-posh/releases/tag/v26.0.0) 之后，  
  `oh-my-posh init nu` 就不在 `~` 中创建配置文件而是在 `$nu.data-dir` 的 `vendor` 目录中创建了。
- Oh My Posh 文档的 [Getting Started > Get started > prompt](https://ohmyposh.dev/docs/installation/prompt) 章节提示用户  
  应该在 `$nu.config-path` 中写入 `oh-my-posh init nu`（推荐带 `--config` 参数以应用指定主题），  
  但是这样会在每次打开 shell 时都生成并覆写之前 `oh-my-posh.nu` 配置文件，我没有采用。
- 仅在 PowerShell 中使用 Oh My Posh 的话不需要 `.oh-my-posh.nu` 文件。

## 粉红色

FBAED2
FFA6C9
F985BB

windows:

深：F76CAD
淺：FA85BA

## 终端字体行高

23PX / 17 \* 1.35
