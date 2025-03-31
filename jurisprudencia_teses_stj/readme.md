# Extração e Análise da Jurisprudência em Teses do STJ

Este documento descreve o processo de extração e análise da jurisprudência em teses do Superior Tribunal de Justiça (STJ), utilizando o feed RSS do STJ e exportando edições relevantes para análise. Siga as instruções abaixo para utilizar o fluxo de trabalho.

## Pré-requisitos

- Acesso à internet.
- Navegador para acessar o site do STJ.
- Ferramenta para leitura de feeds RSS.
- Permissão para exportar documentos do site do STJ.

## Passos para Extração e Análise da Jurisprudência em Teses

### 1. Identificação do Tema Desejado no RSS Feed do STJ

- Acesse o feed RSS do STJ.
- Localize a seção específica sobre "Jurisprudência em Teses".
- Identifique o tema desejado que será analisado.

### 2. Acesso ao Site do STJ

- Abra o navegador e acesse o [site do STJ](https://www.stj.jus.br).
  
### 3. Navegação até as Edições do Tema

- No menu principal, localize a seção de "Jurisprudência".
- Clique na opção "Jurisprudência em Teses".

### 4. Seleção e Exportação das Edições

- Após acessar a seção de "Jurisprudência em Teses", você verá uma lista de edições disponíveis.
- Selecione todas as edições relevantes para o tema identificado.
- Procure pela opção de exportação e selecione "Exportar para PDF". Salve os arquivos no seu dispositivo.

### 5. Exportação para TXT

- Repita o processo de exportação, mas desta vez selecione a opção "Exportar para TXT". Salve o arquivo de texto.

### 6. Envio como Contexto para o Pattern `jurisprudencia_teses_stj`

- Com o arquivo TXT salvo, você pode agora enviar seu conteúdo como contexto para o padrão `jurisprudencia_teses_stj`.
- Utilize o fluxo `doismill jurisprudencia_teses_stj` para processar o documento.

### 7. Criação do Documento

- O documento será automaticamente criado com a ementa e frontmatter na pasta indicada no fluxo.
- Verifique a pasta para garantir que o documento foi criado corretamente.

## Conclusão

Seguindo esses passos, você poderá extrair e analisar a jurisprudência em teses do STJ de maneira eficiente. Certifique-se de ter as permissões necessárias para acessar e exportar os dados do site do STJ.

atualizado em 2024-09-27