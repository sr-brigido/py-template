# Padrão de documentação para projetos em Python

Utilize esse modelo para criar a documentação dos seus projetos em `Python`.

## Layout base do projeto (pastas e arquivos na raiz do repositório)

    .git/                       # Pasta referente a administração de branchs, commits e pre-commits do git.
    .github/                    # Pasta com as configurações que tangem o repositório remoto (políticas de CI, etc...)
    .venv/                      # Pasta com os arquivos referentes ao ambiente virtual do projeto
    .vscode/                    # Pasta com configuraçõs da IDE para o projeto (Opcional.)
    docs/                       # Pasta com os arquivos .md que definem a estrutura da documentação
    src/                        # Pasta onde se encotram os arquivos de código fonte do projeto
    tests/                      # Pasta contendo os testes unitários, de funcionalidade e de integração

    .gitignore                  # Arquivo referente aos arquivos/pastas que não serão trackeados pelo git
    .pre-commit-config.yaml     # Arquivo de configuração dos hooks de pre-commit do projeto
    .python-version             # Arquivo que orienta o pyenv a setar a versão correta do Python
    LICENCE                     # Arquivo de licença de distribuição
    mkdocs.yml                  # Arquivo de configuração do Mkdocs para estruturar a documentação do projeto
    pyproject.toml              # Arquivo geral do projeto onde constam os autores, o nome do projeto, as dependencias diretas e de desenvolvimento
    README.md                   # Arquivo README para setup inicial do projeto
