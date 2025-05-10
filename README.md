# Código fonte de vscodium.com

Este repositório contém o código fonte do [<i>site</i> da Web www.vscodium.com](https://www.vscodium.com).


## Processo de criação

O <i>site</i> da Web utiliza [Jekyll](https://jekyllrb.com/), um mecanismo de <i>site</i> da Web estático que compila
o modelo jekyll para um <i>site</i> da Web <b>html</b> estático.

## Como transferir e testar o <i>site</i> da Web no servidor local (<i>localhost</i>)


### Clonar o repositório
```
git clone https://github.com/VSCodium/vscodium.github.io

cd vscodium.github.io
```

### Instalar jekyll e inicie o servidor de desenvolvimento

Instale jekyll do [<i>site</i> da Web oficial](https://jekyllrb.com/)

Ou utilize o gestor de pacotes da sua distribuição GNU/Linux (exemplo, `sudo apt install jekyll`)

e execute o seguinte comando dentro da fonte do <i>site</i> para iniciar um serviço temporário

```
jekyll serve
```

depois abre um navegador e vá para

[http://localhost:4000](http://localhost:4000)


### Criar e implementar o código estático

Execute o seguinte comando dentro da fonte jekyll

```
jekyll build
```

e mova o conteúdo da pasta **_site** na raiz do seu servidor da Web para implementar o <i>site</i> da Web
