# Setup básico de projetos em Python
Este repositório tem como objetivo auxiliar os desenvolvedores de novas tecnologias a construir um melhor código seguindo as boas práticas da [PEP8](https://peps.python.org/pep-0008/).

>Versão 1.0.0 | Autor: Gabriel Ronchi Brigido

## Pré-requisitos
- Para o versionamento e reastreabiliade do código use o **Git**, instalação [aqui](https://git-scm.com)
- Para edição facilitada do código use o **VSCode**, instalação [aqui](https://code.visualstudio.com/)
- Para melhor controle de versões de instalação do *Python* use o **Pyenv**, guia de instalação [aqui](https://www.youtube.com/watch?v=HTx18uyyHw8)
- Para gerenciamento de pacotes de dependências use o **Poetry**, consulte a  documentação [aqui](https://python-poetry.org/docs/)

## Ajustando o ambiente e acessando a documentação

Uma vez com os pré-requisitos atendidos você pode clonar este repositório para um repositório local na sua máquina e começar seu projeto a partir dele

- Clone o repositório:

```bash
git clone https://github.com/Pavei-Brands/setupProjetosPaveiPython.git
cd setupProjetosPaveiPython     #Navegue até a pasta do projeto
```

- Uma vez no diretório, execute os comandos do `Poetry` para acessar a documentação com os detalhes da base do projeto

```bash
poetry config virtualenvs.in-project true   #Comando para criar os ambientes virtuais dentro do projeto
poetry config virtualenvs.prefer-active-python true #Comando para o poetry identificar a versão do python utilizada do projeto
```
```bash
poetry install --no-root    #instalar as dependencias base do projeto
```
```bash
poetry run task docs    #iniciar a instancia da documentação
```

**Uma vez iniciada a documentação, você pode acessá-la [aqui](http://localhost:8000).**

Pressione `Ctrl+C` para fechar a documentação.

## Contato

Para sugestões, dicas e feedbacks utilize o seguinte email:

**Gabriel Ronchi Brigido** - [gabriel.brigido@gbinteligencia.com](mailto:gabriel.brigido@gbinteligencia.com)
