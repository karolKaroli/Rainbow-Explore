# RepositorioTemplate

Repositório que deve ser utilizado como template inicial pelos grupos da Disciplina de Engenharia de Software III (Arquitetura de Software) do IFPI Campus Pedro II, ministrada pelo Prof. Cleber Araújo. **Atenção: Renomeie o seu repositório para (Ano.Semestre)(Grupo)(NomeDoProjeto).** 

(Apague esta seção)

# NomedoProjeto
**Número do Grupo:** XX
**Disciplina:** xx
**Professor:** xx


## Alunos
| Matrícula   | Aluno             |
|-------------|-------------------|
| xx/xxxxxx   | xxxx xxxx xxxxx  |
| xx/xxxxxx   | xxxx xxxx xxxxx  |

## Sobre
Descrição geral do seu projeto.

## Screenshots
![Screenshot 1](URL_da_Imagem_1)
![Screenshot 2](URL_da_Imagem_2)
![Screenshot 3](URL_da_Imagem_3)

## Instalação
**Linguagens:** xxxxxx
**Tecnologias:** xxxxxx

Descreva os pré-requisitos para rodar o seu projeto e os comandos necessários. Insira um manual ou um script para auxiliar ainda mais.

## Uso
Explique como usar o seu projeto, caso haja algum passo a passo após o comando de execução.

## Vídeo
Adicione 1 ou mais vídeos demonstrando a execução do projeto final.

## Principal(is) Metodologia(s) Adotada(s)
- Exemplo.: Scrum

## Principais Linguagens Utilizadas e/ou Pretendidas
- Exemplo.:JavaScript
- Exemplo.: Python

## Principais Tecnologias Utilizadas e/ou Pretendidas
- Exemplo: React
- Exemplo: Django

## Principal(is) Estilo(s) Arquitetural(is) Adotado(s)
- Exemplo: MTV - Model Template View

## O Projeto está rodando?
( ) SIM (x) NÃO





## RepositorioTemplate

Repositório que deve ser utilizado como template inicial pelos grupos da Disciplina de **Engenharia de Software III** (Arquitetura de Software) do IFPI Campus Pedro II, ministrada pelo **Prof. Cleber Araújo**.

## Introdução

Este repositório traz um template de documentação a ser seguido pelos grupos.

## Tecnologia

A geração do site estático é realizada utilizando o [MkDocs](https://www.mkdocs.org/).

> "MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation."

### Instalando o MkDocs

Para instalar o MkDocs, você pode executar o comando:

```shell
pip install mkdocs
```

Para mais detalhes, consulte o [Guia de Instalação](#).

# Criando um Novo Projeto

Começar é super fácil. Para criar um novo projeto, execute o seguinte comando a partir da linha de comando:

```shell
mkdocs new meu-projeto
cd meu-projeto
```

Dê um momento para revisar o projeto inicial que foi criado para você.

## Estrutura Inicial do MkDocs

Existe um único arquivo de configuração chamado `mkdocs.yml` e uma pasta chamada `docs`, que conterá os arquivos de origem da sua documentação (o valor padrão para a configuração `docs_dir` é `docs`). No momento, a pasta `docs` contém apenas uma página de documentação, chamada `index.md`.

O MkDocs vem com um servidor de desenvolvimento integrado que permite visualizar sua documentação enquanto você trabalha nela. Certifique-se de estar no mesmo diretório do arquivo de configuração `mkdocs.yml` e, em seguida, inicie o servidor executando o comando `mkdocs serve`:

```shell
$ mkdocs serve
```

```shell
INFO    -  Construindo documentação...
INFO    -  Limpando o diretório do site
INFO    -  Documentação construída em 0.22 segundos
INFO    -  [15:50:43] Observando alterações nos caminhos: 'docs', 'mkdocs.yml'
INFO    -  [15:50:43] Servindo em http://127.0.0.1:8000/
```

Abra [http://127.0.0.1:8000/](http://127.0.0.1:8000/) no seu navegador, e você verá a página inicial padrão sendo exibida:

![O servidor MkDocs ao vivo](http://127.0.0.1:8000/)

O servidor de desenvolvimento também suporta recarregamento automático e reconstruirá sua documentação sempre que algo no arquivo de configuração, diretório de documentação ou diretório do tema for alterado.

Abra o documento `docs/index.md` no seu editor de texto preferido, altere o título inicial para "MkLorum" e salve suas alterações. Seu navegador recarregará automaticamente e você verá sua documentação atualizada imediatamente.

Agora tente editar o arquivo de configuração: `mkdocs.yml`. Altere a configuração `site_name` para "MkLorum" e salve o arquivo.

```yaml
site_name: MkLorum
site_url: https://example.com/
```
