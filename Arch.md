# Arch

Bem vindo ao guia de instalação do Arch

# ArchInstall
para instalar com o archinstall siga o guia abaixo

# Keymaps

keymaps são basicamente o teclado que você usa, por padrão sempre vai estar em inglês, você deve setar sua keymap para o brasileiro para poder usar por exemplo "Ç", o default do brasil é br-abnt2

```localectl list-keymaps``` - localiza todas as keymaps utilizáveis

```localectl list-keymaps | grep -i (keymap)``` - localiza as keymaps e pega com grep as palavras setadas no (keymap) exemplo: ```localectl list-keymaps | grep -i br``` - para procurar por keymaps que tenham ```br``` no nome

# Iwctl

depois de setar seu keymap você deve configurar a network usando iwctl

```iwctl``` - para entrar no modo iwctl e poder configurar as redes

```devicelist``` - lista os seus devices por exemplo "wlan0"

```station wlan0 get-networks``` -  lista/pega as networks disponíveis em "wlan0" troque wlan0 pelo seu device certo, veja em ```devicelist```

```station wlan0 connect (network)``` - conecta a network digitando o nome completo dela em (network), para ver as networks disponiveis: ```station (device) get-networks```
