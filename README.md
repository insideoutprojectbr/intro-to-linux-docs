# intro-to-linux-docs

Documentação do evento de Introdução à Linux.

##Créditos
[Thaíssa Falbo](https://github.com/tfalbo)

Forked from [tfalbo/intro-to-linux-docs](http://github.com/tfalbo/intro-to-linux-docs)

##Contribua

Documentação gerada usando [MkDocs](http://www.mkdocs.org/)

##Instalação

### Usando virtualenv

```bash
pip install virtualenv 
venv  --python python3 venv # cria o virtualenv do projeto 
. venv/bin/activate # ativa o virtualenv
pip install -r requirements.txt #instala as dependências do projeto
```

### Rodando localmente

```bash
mkdocs serve # executa servidor localmente em http://127.0.0.1:8000

```

### Publicando no GithubPages

```bash
mkdocs gh-deploy --clean
```
