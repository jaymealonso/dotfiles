# Dotfiles 

Estes dotfiles foram criados em formato de diretorio usando GNU stow. Mais informação na respectiva [seção](#instalação-stow)

> **Atenção VERIFIQUE a data de ultima atualização desse readme para ver se existe alguma instrução desatualizada**

Verificar se essas ferramentas estão instaladas ants de executar o stow

> link: [Instalações](docs/instalacoes.md)

# Instalação STOW

Estes dotfiles foram criados em formato de diretorio usando GNU stow. https://www.gnu.org/software/stow/. 

Essa ferramenta permite que você mantenha seus dotfiles em um diretório e os instale em seu sistema via [symlinks](https://en.wikipedia.org/wiki/Symbolic_link). Possibilitando o armazenamento de configurações em um único lugar, facilitando a manutenção e a atualização dos dotfiles entre diferentes sistemas.


Instalar o stow:
```
sudo apt install stow
```

Para fazer deploy dos dotfiles:
```
stow -t ~ <nome_do_diretório>
```

diretórios nesse repositório:   
| Diretório | Descrição | Comando |
| --- | --- | --- |
| docs |  Documentação adicional | - |
| oh-my-zsh | Configurações do oh-my-zsh  | ```stow -t ~ oh-my-zsh```
| neovim | Configurações do neovim | ```stow -t ~ neovim```
| ranger | Configurações do ranger file manager | ```stow -t ~ ranger```
| scripts | Scripts úteis ver [abaixo](#scripts). | ```stow -t ~ scripts```
| tmux | Configurações do tmux, ativar uso do mouse e outros. | ```stow -t ~ tmux```
| zsh | Configurações do zsh | ```stow -t ~ zsh```

## Scripts

| Nome | Descrição | link |
| --- | --- | --- |
| cht.sh | Permite fazer uma pesquisa rapida sobre alguns comandos e formatos mais usados diretamente no terminal | https://cht.sh/ |
| tmux-sessionizer | Script para criar uma sessão do tmux com o nome da pasta atual. É uma copia do arquivo criado pelo The Primagen | [github do The Primagen](https://github.com/ThePrimeagen/.dotfiles/blob/master/bin/.local/scripts/tmux-sessionizer) |

## Eclipse windows vrapper

| Nome | Descrição | link |
| --- | --- | --- |
| .vrapperrc | Script de configuracao do vrapper no windows | https://vrapper.sourceforge.net/home/ |




