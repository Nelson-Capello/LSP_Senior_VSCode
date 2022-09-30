# `LSP Senior Syntax Highlighting no VSCode README`

Extensão para syntax highlighting da LSP - Linguagem de Programação Senior da Senior Sistemas, tecnologia G5, para o VSCode.

## `DISCLAIMER`:

Este projeto está sendo desenvolvido de forma independente e não tem nenhuma ligação, vínculo ou relação com a empresa Senior Sistemas, detentora da tecnologia da linguagem LSP e dos sistemas que a utilizam.

A intenção é que Consultores que desejam utilizar o VSCode ao invés do Editor de Regras da Tecnologia G5 da Senior o possam fazer com mais produtividade e desenvoltura, e que o projeto possa evoluir para contemplar também os snippets da linguagem, facilitando o uso para Consultores iniciantes.

## Features

Faz a coloração do código conforme palavras reservadas, variáveis, funções, etc.

Futuramente pretendo ter os snippets da linguagem também disponíveis.

## Requirements

Precisa obviamente do VSCode para funcionar, para instalar basta copiar os arquivos para a pasta de extensions do VSCode.

Procedimento:
- vai criar uma pasta chamada lsp dentro de extensions;
- vai precisar copiar para dentro dessa pasta lsp o seguinte:
  - pasta images;
  - pasta syntaxes;
  - arquivos:
    - changelog.md;
    - readme.md;
    - language-configuration.json;
    - package.json;

## Extension Settings

Não precisa de nenhuma configuração adicional para funcionar, apenas associar com a linguagem lsp, no VSCode.

## Known Issues

Infelizmente não há uma forma de abrir as regras diretamente dos objetos da Senior, então, tem que abrir a regra no editor, copiar, colar no VSCode, editar, copiar e colar de volta no editor de regras da G5. Essa é uma limitação da tecnologia G5 da Senior.

## pendênmcias ou problemas a serem resolvidos:

- tem alguns temas que as palavras reservadas para variáveis aparecem em cor diferente, como alfa e inteiro;
- tem que incluir as variáveis do financeiro por exemplo, as FinPEetcetc;

## Releases:

Para observações sobre releases, atualizações, correções, etc, ver arquivo Changelog.md.