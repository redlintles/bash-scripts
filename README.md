# bash-scripts
Um repositório com bash scripts úteis que podem ser instalados facilmente no seu sistema linux


## Como usar

primeiro clone o repositório com git clone <url>;

Existe um arquivo principal de nome "doLinks" que cria links símbólicos de todos os scripts na pasta $Home/bin, certifique-se de que ela já esteja criada e incluída no PATH

caso não esteja, rode os seguintes comandos

```sh
mkdir $HOME/bin
export PATH="$HOME/bin:$PATH"
source $HOME/.bashrc
```

uma vez que isto foi feito, basta rodar o script doLinks(bash ./doLinks), que ele tratará de criar todos os links símbolícos para os scripts deste repositório, assim eles podem ser facilmente invocados do terminal

Abaixo segue uma lista com um resumo de todos os scripts deste repositório.

