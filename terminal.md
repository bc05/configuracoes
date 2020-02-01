# Ferramentas e plugins para otimizar uso do terminal no MacOs

## Oh my zsh

 - O Oh My Zsh é uma estrutura agradável, de código aberto e orientada pela comunidade para gerenciar sua configuração do Zsh. Ele vem com milhares de funções úteis, ajudantes, plugins, temas e algumas coisas que fazem você gritar ...

 ### Como instalar

 - O [site oficial](https://ohmyz.sh/) possui um guia de como realizar a instalação.

 ### Plugins

 - O [Zinit](zinit) permite instalar uma série de plugins no zsh. Para realizar a instalação, basta seguir o tutorial disponível no [link](https://github.com/zdharma/zinit#option-1---automatic-installation-recommended).

 - Com o Zinit instalado,edite o arquivo `.zshrc` adicionando as linhas abaixo:
 ```sh
    zplugin  light zsh-users/zsh-autosuggestions
    zplugin  light zsh-users/zsh-completions
    zplugin  light zdharma/fast-syntax-highlighting 
 ``` 
  Feche o terminal e abra novamente. Note que os plugins serão instalados.

  Pronto, agora você tem um terminal tunado e pronto para uso.