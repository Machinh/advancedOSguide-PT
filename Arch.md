# Arch

Bem vindo ao guia de instalação do Arch

# ArchInstall
para instalar com o archinstall siga o guia abaixo

# Keymaps

keymaps são basicamente o teclado que você usa, por padrão sempre vai estar em inglês, você deve setar sua keymap para o brasileiro, o default do brasil é br-abnt2

```localectl list-keymaps``` - localiza todas as keymaps utilizáveis

```localectl list-keymaps | grep -i (keymap)``` - localiza as keymaps e pega com grep as palavras setadas no (keymap) exemplo: ```localectl list-keymaps | grep -i br``` - para procurar por keymaps que tenham ```br``` no nome
