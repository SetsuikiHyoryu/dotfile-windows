# Windows Dotfile

## Nushell

### Nushell 中配置 Oh My Posh 的操作流程

1. 确保 Nushell 本身正常运行。
2. 确保用户目录下有自己配置好的 `.poshthemes/` 目录。
   - `.poshthemes/`: Oh My Posh 主题存放目录。
3. 在 Nushell 命令行窗口中执行  
   `oh-my-posh init nu --config ~/.poshthemes/tokyo_mine.omp.json` 即可。
   - 此命令见于 Nushell 中使用 Oh My Posh 的文档：  
     <https://www.nushell.sh/book/3rdpartyprompts.html#oh-my-posh>
   - Oh My Posh 文档的  
      [Getting Started > Get started > prompt](https://ohmyposh.dev/docs/installation/prompt) 章节  
      提示用户应该在 `$nu.config-path` 中写入 `oh-my-posh init nu`  
     （推荐带 `--config` 参数以应用指定主题），  
      但是这样会在每次打开 shell 时都生成并覆写之前 `oh-my-posh.nu` 配置文件，我没有采用。
   - oh-my-posh 在 [v26.0.0](https://github.com/JanDeDobbeleer/oh-my-posh/releases/tag/v26.0.0) 之后，  
     `oh-my-posh init nu` 就不在 `~` 中创建配置文件而是在 `$nu.data-dir` 的 `vendor` 目录中创建了。

## GlazeWM

开机自启动：

1. WIN + R 后输入 `shell:startup` 打开启动文件夹。
2. `which glazme` 找到程序路径。
3. 创建 `glzme.exe` 的快捷方式，并放入 startup 目录。

## 粉红色

FBAED2
FFA6C9
F985BB

windows:

深：F76CAD
淺：FA85BA

## 终端字体行高

23PX / 17 \* 1.35

## 实用命令

- tasklist: 打印 Process (task) 。
- findstr: 找字符串。
