# task-completions

> zsh 配置 completions. 支持 tab 智能补全提示

### install

- clone

```
git clone git@github.com:yangyang5214/task-completions.git ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/task
```

- add task plugin

```
# vim ~/.zshrc

# 追加 task
plugins=(git task)

# 终端运行
autoload -U compinit && compinit
```

### usage

> 配置后，支持 tab 补全

[![asciicast](https://asciinema.org/a/9fSVGQwH13L2c0DmOUH8D8LMp.svg)](https://asciinema.org/a/9fSVGQwH13L2c0DmOUH8D8LMp)
