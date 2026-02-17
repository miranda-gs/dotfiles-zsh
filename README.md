# 🚀 Pré-requisitos para Utilizar o `.zshrc`

Antes de importar e utilizar seu arquivo `~/.zshrc`, é importante garantir que algumas dependências estejam instaladas na sua máquina. Este guia apresenta as dependências necessárias e exemplos de como instalá-las no Arch Linux.

## 📦 Dependências

- **⚡ fastfetch**  
  Ferramenta para exibir informações do sistema no terminal.

- **🐱 fastcat**  
  Framework para alterar imagem exibida no fastfetch.

- **🌐 curl**  
  Ferramenta para transferências de dados via linha de comando.

- **🗜️ unzip**  
  Utilitário para descompactar arquivos `.zip`.

- **💻 zsh**  
  Shell avançado, recomendado para uma experiência mais rica no terminal.

- **🔌 zinit**  
  Gerenciador de plugins para o Zsh. Necessário para carregar plugins e temas no `.zshrc`.

- **🖋️ JetBrains Nerd Font Mono**  
  Fonte compatível com Nerd Fonts, utilizada para melhorar a exibição de símbolos e ícones no terminal.

---

## 🏗️ Como instalar no Arch Linux

Use o `pacman` para instalar os pacotes disponíveis nos repositórios oficiais:

```bash
sudo pacman -S fastfetch fastcat curl unzip zsh
```

### 🔌 Instalando o Zinit

O Zinit não está nos repositórios oficiais. Instale utilizando o comando oficial:

```bash
sh -c "$(curl -fsSL https://git.io/zinit-install)"
```

### 🖋️ Instalando a JetBrains Nerd Font Mono

No Arch Linux, a JetBrains Nerd Font Mono pode ser instalada pelo AUR (Arch User Repository) usando, por exemplo, o `yay`:

```bash
yay -S nerd-fonts-jetbrains-mono
```

Se ainda não possui o `yay`, consulte as instruções de instalação [aqui](https://github.com/Jguer/yay).

---

### ⚠️ Observação Importante sobre WSL2

Se você estiver utilizando **WSL2** no Windows, a instalação da fonte **JetBrains Nerd Font Mono** deve ser feita **no próprio Windows** — não no ambiente Linux.

Passos recomendados:

1. Baixe a fonte no site oficial do [Nerd Fonts](https://www.nerdfonts.com/font-downloads).
2. Instale-a no Windows clicando duas vezes sobre o arquivo `.ttf` e escolhendo "Instalar".
3. Abra o Windows Terminal, vá em "⚙️ Configurações", selecione o perfil do Ubuntu/WSL, e ajuste a fonte para "JetBrainsMono Nerd Font".

**Assim, os ícones e símbolos aparecerão corretamente no terminal do Windows.**

---

## ✅ Após instalar as dependências

Após seguir os passos acima, você já pode importar seu arquivo `~/.zshrc` e aproveitar os recursos do seu ambiente personalizado! ✨

---
