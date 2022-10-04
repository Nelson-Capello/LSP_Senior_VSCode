# `LSP Senior Syntax Highlighting no VSCode README`

Extensão para syntax highlighting da LSP - Linguagem de Programação Senior da Senior Sistemas, tecnologia G5, para o VSCode.

## `DISCLAIMER`:

Este projeto está sendo desenvolvido de forma independente e não tem nenhuma ligação, vínculo ou relação com a empresa Senior Sistemas, detentora da tecnologia da linguagem LSP e dos sistemas que a utilizam.

A intenção é que Consultores que desejam utilizar o VSCode ao invés do Editor de Regras da Tecnologia G5 da Senior o possam fazer com mais produtividade e desenvoltura, e que o projeto possa evoluir para contemplar também os snippets da linguagem, facilitando o uso para Consultores iniciantes.

## Features

Faz a coloração do código conforme palavras reservadas, variáveis, funções, etc.

Futuramente pretendo ter os snippets da linguagem também disponíveis.

## Vantagens de trabalhar com LSP no VSCode ao invés do Editor de Regras:

Principalmente, a disponibilidade de funcionalidades modernas de desenvolvimento, utilização de temas, plugins, extensões, controle de versão (GitHub), etc, e os avançados recursos de edição disponíveis no VSCode, voltado para desenvolvedores.

Para trabalhar com LSP no VSCode, recomendo utilizarem também a extensão Numbered Bookmarks, que implementa os bookmarks da mesma forma que o editor de regras da Senior, ctrl+shift+numero cria ou exclui, ctrl+numero navega. Tem a vantagem de salvar os bookmarks com o projeto, então, quando vc reabrir o seu arquivo .lsp, eles vão estar lá.

## Requirements

Precisa obviamente do VSCode para funcionar, para instalar basta copiar os arquivos para a pasta de extensions do VSCode.

## Como Instalar:

Procedimento:
- baixar os arquivos aqui do repositório, não precisa ser todos, mas por praticidade, pode baixar o .zip em Code - download ZIP; talvez um dia eu faça um release com o .zip pronto com tudo o que precisa.

- Se baixou o .zip do GitHub:
  - descompactar na pasta extensions do VSCode (aqui funcionou em %LocalAppData%\Programs\Microsoft VS Code\resources\app\extensions\);
  - renomear a pasta que o .zip cria para 'lsp' (sem as '');
    - vai ser algo como LSP_Senior_VSCode-main, renomear para lsp;
  - as seguintes pastas e arquivos não são necessárias para o funcionamento e podem ser excluídos (opcional):
    - .vscode;
    - .gitignore;
    - .vscodeignore;
    - vsc-extension-quickstart.md;
    - .gitattributes;

- Instalação Manual:
  - vai criar uma pasta chamada lsp dentro de extensions;
  - vai precisar copiar para dentro dessa pasta lsp os seguintes arquivos e pastas:
    - pasta images e seu conteúdo;
    - pasta syntaxes e seu conteúdo;
    - arquivos:
      - changelog.md;
      - readme.md;
      - language-configuration.json;
      - package.json;

## Extension Settings

Não precisa de nenhuma configuração adicional para funcionar, apenas associar com a linguagem lsp, no VSCode.
Se, ao gravar os arquivos, utilizar extensão .lsp, eles são automaticamente reconhecidos como LSP Senior e a extensão é automaticamente ativada.

## Known Issues

Infelizmente não há uma forma de abrir as regras diretamente dos objetos da Senior, então, tem que abrir a regra no editor, copiar, colar no VSCode, editar, copiar e colar de volta no editor de regras da G5. Essa é uma limitação da tecnologia G5 da Senior.

## Pendências, problemas, dúvidas e sugestões:

- Ver "issues" no GitHub;
- Se encontrar algum problema, tiver alguma dúvida ou sugestão, por favor abra um issue :) assim vc ajuda na melhoria da funcionalidade.
- O projeto é público, fique à vontade para criar seu fork se desejar, mas se a sua versão ficar melhor que a minha, me avise!
- Da mesma forma, quem quiser contribuir também é bem vindo! Como em todo projeto com mais de um participante, haverá moderação para as implementações, mas, de forma bem democrática, sugestões e opiniões serão sempre bem-vindas.

## Releases:

Para observações sobre releases, atualizações, correções, etc, ver arquivo Changelog.md.
