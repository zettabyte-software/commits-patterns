# commits-patterns

## Introdução

Esse arquivo tem a inteção de documentar e oficializar a padronização dos commits dos projetos da Zettabyte, baseados na [convenção de commits](https://www.conventionalcommits.org/pt-br/v1.0.0-beta.4/), com algumas peculiaridades.

## Prefixos

1. **feat**: nova funcionalidade desenvolvida
1. **fix**: correção de algum bug
1. **docs**: atualização/criação de uma documentação de alguma funcionalidade, seja em _README.md_ ou comentários no próprio código
1. **build**: alterações em arquivos de build - como arquivos Docker ou Kubernets, por exemplo - focadas no ambiente de produção
1. **ci**: alterações voltadas para configuração do CI ou CD da aplicação
1. **del**: deleção de arquivos
1. **comments**: altearções voltadas a comentários no próprio código
1. **style**: alterações que não afetam a funcionalidade do código em si, mas a forma na qual o código será disposto - linhas em branco, identação, última linha em branco no final do arquivo
1. **test**: alterações voltadas para criação ou correção de testes
1. **migrations**: arquivos de migrações do backend
1. **refactor**: alterações que não visam alterações de funcionalidade, mas sim uma melhor otimização e/ou performance do código
1. **deps**: adição ou remoção das dependências - normalemte serão comitados arquivos como **package.json** e **requirements.txt**
2. 1. **dev**: configurações para o desenvolvimento - arquivos para devcontainers, debbugers, etc
