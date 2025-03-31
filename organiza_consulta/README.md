# Padrão Fabric para Organização de Consultas Jurídicas

## O que este padrão faz

Este padrão Fabric automatiza a organização de consultas jurídicas iniciais, transformando notas simples em documentos estruturados no Obsidian. Ele:

1. Analisa o conteúdo da consulta inicial
2. Gera uma estrutura padronizada para a nota
3. Adiciona metadados relevantes
4. Organiza as informações em seções lógicas (contexto, fatos relevantes, análise preliminar, etc.)

## Como utilizar

1. Abra uma nova nota no Obsidian.
2. Anote a consulta nos exatos termos em que foi feita.
3. Contextualize com data e a situação jurídica.
4. No terminal, certifique-se de estar no diretório onde deseja salvar a nota organizada.
5. Use o comando abaixo para processar a nota:

   ```
   cat /caminho/para/sua/nota.md | organize_consultas > nota_organizada.md
   ```

   Ou, se preferir usar xclip (assumindo que o conteúdo da nota está na área de transferência):

   ```
   xclip -o | organize_consultas > nota_organizada.md
   ```

6. Renomeie a nota gerada seguindo o formato: `YYYY-MM-DD nome da nota.md`
   Por exemplo: `2024-09-06 Consulta sobre Concurso Público.md`

7. Abra a nota organizada no Obsidian e revise o conteúdo.

## Dicas

- Certifique-se de incluir todas as informações relevantes na nota inicial.
- O padrão funciona melhor com consultas detalhadas e bem contextualizadas.
- Revise sempre a saída gerada para garantir precisão e completude.

## Requisitos

- Obsidian instalado
- Comando `organize_consultas` configurado no seu sistema
- xclip (opcional, para usar conteúdo da área de transferência)

## Suporte

Para problemas ou sugestões, abra uma issue no repositório do projeto.

---

Criado com [Fabric](https://github.com/danielmiessler/fabric) 🤖