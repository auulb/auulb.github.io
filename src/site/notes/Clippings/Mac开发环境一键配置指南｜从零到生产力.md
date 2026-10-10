---
{"dg-publish":true,"permalink":"/Clippings/Mac开发环境一键配置指南｜从零到生产力/","title":"Mac开发环境一键配置指南｜从零到生产力","tags":["clippings"],"dg-note-properties":{"title":"Mac开发环境一键配置指南｜从零到生产力","source":"https://zhuanlan.zhihu.com/p/1979933222306591061","author":["[[花宝宝​]]"],"published":null,"created":"2026-10-10","description":"新Mac到手，环境配置是个大工程。 这篇整理了我的配置流程和脚本，争取2小时搞定所有开发环境。 一、系统设置先调整一些系统设置，提升效率。 1.1 终端执行# 显示隐藏文件 defaults write com.apple.finder AppleS…","tags":["clippings"]}}
---

[收录于 · 技术急诊室：从线上故障到架构实战](https://www.zhihu.com/column/c_1982067831853036046)

35 人赞同了该文章

新Mac到手， [环境配置](https://zhida.zhihu.com/search?content_id=267206080&content_type=Article&match_order=1&q=%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3OTE4MTY3NzksInEiOiLnjq_looPphY3nva4iLCJ6aGlkYV9zb3VyY2UiOiJlbnRpdHkiLCJjb250ZW50X2lkIjoyNjcyMDYwODAsImNvbnRlbnRfdHlwZSI6IkFydGljbGUiLCJtYXRjaF9vcmRlciI6MSwiemRfdG9rZW4iOm51bGx9._V3vmTUV46Ovod57r5WrIk1Uzk32rUiUhCnouxoVfS8&zhida_source=entity) 是个大工程。

这篇整理了我的配置流程和脚本，争取2小时搞定所有开发环境。

---

## 一、系统设置

先调整一些系统设置，提升效率。

### 1.1 终端执行

```
# 显示隐藏文件
defaults write com.apple.finder AppleShowAllFiles -bool true

# Dock自动隐藏，减少延迟
defaults write com.apple.dock autohide -bool true
defaults write com.apple.dock autohide-delay -float 0
defaults write com.apple.dock autohide-time-modifier -float 0.3

# 关闭.DS_Store生成（网络驱动器）
defaults write com.apple.desktopservices DSDontWriteNetworkStores -bool true

# 加快键盘重复速度
defaults write NSGlobalDomain KeyRepeat -int 1
defaults write NSGlobalDomain InitialKeyRepeat -int 10

# 重启Finder和Dock生效
killall Finder
killall Dock
```

### 1.2 手动设置

- **触控板：** 系统设置 → 触控板 → 轻点来点按 ✅
- **三指拖拽：** 辅助功能 → 指针控制 → 触控板选项 → 拖移样式
- **键盘：** [修饰键](https://zhida.zhihu.com/search?content_id=267206080&content_type=Article&match_order=1&q=%E4%BF%AE%E9%A5%B0%E9%94%AE&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3OTE4MTY3NzksInEiOiLkv67ppbDplK4iLCJ6aGlkYV9zb3VyY2UiOiJlbnRpdHkiLCJjb250ZW50X2lkIjoyNjcyMDYwODAsImNvbnRlbnRfdHlwZSI6IkFydGljbGUiLCJtYXRjaF9vcmRlciI6MSwiemRfdG9rZW4iOm51bGx9.Ymep2lhk5i3YAMqm75kecnhtwdiE8yBL-sugarmAK9U&zhida_source=entity) → Caps Lock改成Control（程序员必备）

---

## 二、Homebrew

Mac的包管理器，必装。

### 2.1 安装

```
# 官方源（可能慢）
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 国内镜像（推荐）
/bin/bash -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```

### 2.2 配置环境变量

```
# M芯片Mac
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

# Intel Mac
echo 'eval "$(/usr/local/bin/brew shellenv)"' >> ~/.zprofile
```

### 2.3 换源（可选）

```
# 中科大源
export HOMEBREW_BREW_GIT_REMOTE="https://mirrors.ustc.edu.cn/brew.git"
export HOMEBREW_CORE_GIT_REMOTE="https://mirrors.ustc.edu.cn/homebrew-core.git"
export HOMEBREW_BOTTLE_DOMAIN="https://mirrors.ustc.edu.cn/homebrew-bottles"
```

---

## 三、命令行工具

### 3.1 一键安装

```
# 基础工具
brew install git wget curl tree htop jq

# 开发工具
brew install vim neovim tmux fzf ripgrep fd bat

# 现代替代品
brew install eza        # 替代ls
brew install zoxide     # 替代cd
brew install tldr       # 替代man
```

### 3.2 Git配置

```
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

# 常用别名
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.lg "log --oneline --graph --all"

# 生成SSH密钥
ssh-keygen -t ed25519 -C "your@email.com"
cat ~/.ssh/id_ed25519.pub
# 复制到GitHub/GitLab
```

---

## 四、终端美化

### 4.1 安装Oh My Zsh

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### 4.2 安装插件

```
# 自动补全
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# 语法高亮
git clone https://github.com/zsh-users/zsh-syntax-highlighting ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

### 4.3 配置.zshrc

```
# 编辑配置
vim ~/.zshrc

# 修改主题（推荐）
ZSH_THEME="agnoster"

# 启用插件
plugins=(
    git
    docker
    kubectl
    zsh-autosuggestions
    zsh-syntax-highlighting
)

# 常用别名
alias ll="eza -la"
alias cat="bat"
alias find="fd"
alias grep="rg"

# 生效
source ~/.zshrc
```

### 4.4 安装Powerlevel10k（可选）

更炫的主题：

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# .zshrc里改主题
ZSH_THEME="powerlevel10k/powerlevel10k"

# 重启终端，按提示配置
```

---

## 五、开发语言环境

### 5.1 Node.js（nvm）

```
# 安装nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

# 重启终端
source ~/.zshrc

# 安装Node
nvm install --lts
nvm use --lts

# 换源
npm config set registry https://registry.npmmirror.com

# 常用全局包
npm install -g pnpm yarn typescript ts-node
```

### 5.2 Python（pyenv）

```
# 安装pyenv
brew install pyenv pyenv-virtualenv

# 配置.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc
echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.zshrc
source ~/.zshrc

# 安装Python
pyenv install 3.11.0
pyenv global 3.11.0

# 换源
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```

### 5.3 Java（jenv）

```
# 安装jenv
brew install jenv

# 配置.zshrc
echo 'eval "$(jenv init -)"' >> ~/.zshrc
source ~/.zshrc

# 安装JDK
brew install openjdk@11 openjdk@17

# 添加到jenv
jenv add /opt/homebrew/opt/openjdk@11/libexec/openjdk.jdk/Contents/Home
jenv add /opt/homebrew/opt/openjdk@17/libexec/openjdk.jdk/Contents/Home

# 设置默认版本
jenv global 17
```

### 5.4 Go

```
brew install go

# 配置环境变量
echo 'export GOPATH=$HOME/go' >> ~/.zshrc
echo 'export PATH=$PATH:$GOPATH/bin' >> ~/.zshrc

# 换源
go env -w GOPROXY=https://goproxy.cn,direct
```

### 5.5 Rust

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
```

---

## 六、Docker

```
# 安装Docker Desktop（官网下载）
# 或者用brew
brew install --cask docker

# 启动Docker Desktop

# 验证
docker --version
docker-compose --version

# 换源（Docker Desktop设置里）
# Registry mirrors: https://mirror.ccs.tencentyun.com
```

---

## 七、数据库客户端

```
# MySQL客户端
brew install mysql-client

# PostgreSQL客户端
brew install libpq
echo 'export PATH="/opt/homebrew/opt/libpq/bin:$PATH"' >> ~/.zshrc

# Redis客户端
brew install redis

# GUI工具（推荐）
brew install --cask dbeaver-community  # 免费，支持多数据库
brew install --cask tableplus          # 付费，颜值高
```

---

## 八、编辑器/IDE

### 8.1 VS Code

```
brew install --cask visual-studio-code

# 命令行启动
# VS Code里：Cmd+Shift+P → Shell Command: Install 'code' command

# 常用插件
code --install-extension ms-python.python
code --install-extension dbaeumer.vscode-eslint
code --install-extension esbenp.prettier-vscode
code --install-extension eamodio.gitlens
code --install-extension ms-azuretools.vscode-docker
```

### 8.2 JetBrains全家桶

```
brew install --cask intellij-idea
brew install --cask pycharm
brew install --cask webstorm
brew install --cask goland
```

---

## 九、其他工具

### 9.1 效率工具

```
# 快捷启动
brew install --cask raycast      # 替代Spotlight

# 窗口管理
brew install --cask rectangle    # 免费

# 剪贴板
brew install --cask maccy        # 免费

# 截图
brew install --cask snipaste
```

### 9.2 开发辅助

```
# API调试
brew install --cask postman
brew install --cask insomnia     # 替代品，更轻量

# 抓包
brew install --cask charles
brew install --cask proxyman     # 替代品，M芯片原生

# SSH管理
brew install --cask termius
```

### 9.3 远程连接

```
# 远程桌面
brew install --cask microsoft-remote-desktop

# 虚拟机
brew install --cask vmware-fusion
```

---

## 十、一键配置脚本

把上面的命令整合成一个脚本：

```
#!/bin/bash
# mac_setup.sh - Mac开发环境一键配置

set -e

echo "🚀 开始配置Mac开发环境..."

# ========== Homebrew ==========
echo "📦 安装Homebrew..."
if ! command -v brew &> /dev/null; then
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    eval "$(/opt/homebrew/bin/brew shellenv)"
fi

# ========== 命令行工具 ==========
echo "🔧 安装命令行工具..."
brew install git wget curl tree htop jq
brew install vim neovim tmux fzf ripgrep fd bat eza zoxide

# ========== Oh My Zsh ==========
echo "💻 安装Oh My Zsh..."
if [ ! -d "$HOME/.oh-my-zsh" ]; then
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "" --unattended
fi

# 插件
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions 2>/dev/null || true
git clone https://github.com/zsh-users/zsh-syntax-highlighting ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting 2>/dev/null || true

# ========== 开发语言 ==========
echo "🐍 安装Python环境..."
brew install pyenv pyenv-virtualenv

echo "📗 安装Node环境..."
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

echo "☕ 安装Java环境..."
brew install openjdk@17 jenv

echo "🐹 安装Go环境..."
brew install go

# ========== Docker ==========
echo "🐳 安装Docker..."
brew install --cask docker

# ========== 编辑器 ==========
echo "📝 安装VS Code..."
brew install --cask visual-studio-code

# ========== 效率工具 ==========
echo "⚡ 安装效率工具..."
brew install --cask raycast rectangle maccy

# ========== 配置 ==========
echo "⚙️ 配置系统..."
defaults write com.apple.finder AppleShowAllFiles -bool true
defaults write com.apple.dock autohide -bool true
killall Finder
killall Dock

echo "✅ 配置完成！请重启终端。"
```

保存为 `mac_setup.sh` ，执行：

```
chmod +x mac_setup.sh
./mac_setup.sh
```

---

## 十一、远程开发

如果你需要连接 [远程服务器](https://zhida.zhihu.com/search?content_id=267206080&content_type=Article&match_order=1&q=%E8%BF%9C%E7%A8%8B%E6%9C%8D%E5%8A%A1%E5%99%A8&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3OTE4MTY3NzksInEiOiLov5znqIvmnI3liqHlmagiLCJ6aGlkYV9zb3VyY2UiOiJlbnRpdHkiLCJjb250ZW50X2lkIjoyNjcyMDYwODAsImNvbnRlbnRfdHlwZSI6IkFydGljbGUiLCJtYXRjaF9vcmRlciI6MSwiemRfdG9rZW4iOm51bGx9.GN90X4sdKhHVCiAQTbf8ro82F0OGk0JyH-s8qy047e0&zhida_source=entity) 开发，推荐：

### 11.1 VS Code Remote

安装Remote-SSH插件，直接在远程服务器上开发。

### 11.2 远程服务器连接

如果服务器在公司内网，可以用组网工具打通：

```
# 本地Mac和公司服务器组网后
# 直接用虚拟IP连接
ssh root@192.168.188.10

# VS Code Remote也可以用
```

我用的 [星空组网](https://zhida.zhihu.com/search?content_id=267206080&content_type=Article&match_order=1&q=%E6%98%9F%E7%A9%BA%E7%BB%84%E7%BD%91&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3OTE4MTY3NzksInEiOiLmmJ_nqbrnu4TnvZEiLCJ6aGlkYV9zb3VyY2UiOiJlbnRpdHkiLCJjb250ZW50X2lkIjoyNjcyMDYwODAsImNvbnRlbnRfdHlwZSI6IkFydGljbGUiLCJtYXRjaF9vcmRlciI6MSwiemRfdG9rZW4iOm51bGx9.7OZCXRA1bnuJ7_rZ_KhfmgqQJwmp30HQYkH93GyhNjg&zhida_source=entity) ，把Mac和公司的开发服务器组到一个网络，在家也能直接SSH连，不用开VPN。

---

## 十二、备份配置

配置好环境后，建议备份：

### 12.1 Homebrew

```
# 导出已安装的包列表
brew bundle dump --file=~/Brewfile

# 恢复
brew bundle --file=~/Brewfile
```

### 12.2 dotfiles

```
# 备份配置文件
mkdir -p ~/dotfiles
cp ~/.zshrc ~/dotfiles/
cp ~/.gitconfig ~/dotfiles/
cp ~/.vimrc ~/dotfiles/

# 传到GitHub
cd ~/dotfiles
git init
git add .
git commit -m "backup dotfiles"
git remote add origin git@github.com:username/dotfiles.git
git push -u origin main
```

---

## 总结

Mac开发环境配置清单：

| 类别 | 工具 |
| --- | --- |
| 包管理 | Homebrew |
| 终端 | Oh My Zsh + Powerlevel10k |
| 版本管理 | nvm/pyenv/jenv |
| 容器 | Docker Desktop |
| 编辑器 | VS Code / JetBrains |
| 效率 | [Raycast](https://zhida.zhihu.com/search?content_id=267206080&content_type=Article&match_order=1&q=Raycast&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3OTE4MTY3NzksInEiOiJSYXljYXN0IiwiemhpZGFfc291cmNlIjoiZW50aXR5IiwiY29udGVudF9pZCI6MjY3MjA2MDgwLCJjb250ZW50X3R5cGUiOiJBcnRpY2xlIiwibWF0Y2hfb3JkZXIiOjEsInpkX3Rva2VuIjpudWxsfQ._xyZ7ABOa_GhJCOrsrGZSTdf6wirbNi2Dv88l2ge8qE&zhida_source=entity) / Rectangle / [Maccy](https://zhida.zhihu.com/search?content_id=267206080&content_type=Article&match_order=1&q=Maccy&zd_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJ6aGlkYV9zZXJ2ZXIiLCJleHAiOjE3OTE4MTY3NzksInEiOiJNYWNjeSIsInpoaWRhX3NvdXJjZSI6ImVudGl0eSIsImNvbnRlbnRfaWQiOjI2NzIwNjA4MCwiY29udGVudF90eXBlIjoiQXJ0aWNsZSIsIm1hdGNoX29yZGVyIjoxLCJ6ZF90b2tlbiI6bnVsbH0._nAGJ8k65WfbBjdOv8gx0SoH2UcgYwfjZ4kcrMwRTLg&zhida_source=entity) |

用一键脚本的话，2小时内可以搞定全部环境。

有问题评论区交流~

发布于 2025-12-04 15:29・北京

赞同 35