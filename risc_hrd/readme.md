# Script de Processamento com Fabric

Este script automatiza a execução de três padrões do `fabric` para processar e organizar o conteúdo copiado da área de transferência, salvando-o em um arquivo de texto e copiando o resultado para a área de transferência novamente. O fluxo é organizado para garantir que a ementa e as tags sejam adicionadas **no início** do arquivo de saída, enquanto o relatório é processado e adicionado ao final.

## Funcionalidade

O script realiza as seguintes operações em sequência:

1. **Executa o padrão `risc_hrd`:**  
   O primeiro padrão a ser executado é `risc_hrd`, que analisa o conteúdo copiado da área de transferência e gera um relatório. Esse relatório é salvo no arquivo de saída.

2. **Gera ementa e tags:**  
   Após o relatório ser processado, o script gera uma ementa (usando o padrão `fabric -p ementa`) e cria as tags (usando o padrão `fabric -p create_tags`). Esses dois blocos são adicionados ao **início** do arquivo de saída.

3. **Copia o conteúdo final para a área de transferência:**  
   O conteúdo completo (ementa, tags e relatório) é copiado para a área de transferência, permitindo fácil reutilização.

## Como funciona

O script utiliza dois arquivos:

- **`output_file`** (`cabeçalho.txt`): O arquivo final onde o conteúdo é salvo.
- **`temp_file`**: Um arquivo temporário usado para gerenciar a ordem dos conteúdos (ementa e tags primeiro, seguido do relatório).

### Estrutura do script

1. **Passo 1:**  
   O script executa o padrão `risc_hrd`, que gera o relatório baseado no conteúdo do clipboard e o salva diretamente no arquivo final `cabeçalho.txt`.

2. **Passo 2:**  
   O script então gera a ementa e as tags. Essas informações são temporariamente salvas no arquivo `temp_cabeçalho.txt`.

3. **Passo 3:**  
   O conteúdo gerado por `risc_hrd` é movido para o final do arquivo temporário. Isso garante que a ementa e as tags sejam inseridas no início, com o relatório vindo em seguida.

4. **Passo 4:**  
   Finalmente, o arquivo temporário substitui o arquivo final, e o conteúdo é copiado para a área de transferência.

## Uso

Para executar o script, basta rodá-lo no terminal. Certifique-se de que você tenha:

1. O comando `xclip` instalado (para acessar a área de transferência).
2. O `fabric` instalado e configurado corretamente.

Execute o script da seguinte maneira:

```bash
./seu_script.sh