# Instalar antes de executar o stow

As ferramantas abaixo tem que ser instaladas antes de se criar o symlink com o stow


### ZSH 

Instruções de instalação em link: https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH

#### 1. oh-my-zsh
Instruções de instalação em link:  https://ohmyz.sh/


#### 2. oh-my-zsh plugin zsh-syntax-highlighting
Plugin para realçar a sintaxe do zsh. link: https://github.com/zsh-users/zsh-syntax-highlighting
```terminal
sudo apt install zsh-syntax-highlighting
```

### Neovim
Editor de texto. É necessaria a versão 0.9.5+.

- Verificar a forma de instalação no site oficial. https://github.com/neovim/neovim

Atualmente estou usando a configuracao do Neovim chamada [Astronvim](https://github.com/AstroNvim/AstroNvim)

Instalar o AstroNvim:
```terminal
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
nvim
:PackerSync
```

### Ranger
File manager para o terminal.
```terminal
sudo apt install ranger
```


### tmux
Gerenciador de sessões de terminal.
```terminal
sudo apt install tmux
```

### FZF
Ferramenta para pesquisar arquivos e comandos no terminal.
```terminal
sudo apt install fzf
```

### LSD (LSDeluxe)
Ferramenta para listar arquivos e diretórios no terminal usando cores e ícones.

link: https://github.com/lsd-rs/lsd
```terminal
sudo apt install lsd
```
