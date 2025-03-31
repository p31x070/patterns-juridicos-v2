# Guia de Classificação de Texto

Este documento descreve as escalas utilizadas para classificar a qualidade de textos em três dimensões principais: **Novidade**, **Clareza** e **Prosa**. Cada escala possui diferentes níveis de avaliação, acompanhados de descrições e exemplos para facilitar a compreensão. As tabelas abaixo estão coloridas com um padrão degradê, onde os valores mais elevados se aproximam dos tons amarelos quase-dourados, facilitando a visualização.

---

## Avaliação de Novidade

<table>
  <thead>
    <tr>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Classificação</th>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Descrição</th>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Exemplos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;"><strong>A - Novo</strong></td>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Inclui novas ideias, propõe novos modelos, liga ideias de forma criativa ou apresenta uma visão significativa do futuro.</td>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">
        - Introdução de novas ideias.<br>
        - Proposta de um novo modelo para resolver um problema.<br>
        - Visão inovadora do futuro.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;"><strong>B - Fresco</strong></td>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;">Propõe novas ideias, mas não atinge as características do nível "A".</td>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;">
        - Expansão útil de ideias existentes.<br>
        - Introdução de conceitos ligeiramente novos.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;"><strong>C - Incremental</strong></td>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;">Expansão ou melhoria de ideias existentes sem criação de novas.</td>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;">
        - Coleções de recursos úteis.<br>
        - Descrições detalhadas do passado.<br>
        - Expansões menores de ideias existentes.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;"><strong>D - Derivado</strong></td>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;">Derivado de ideias bem conhecidas sem novas abordagens ou expansões significativas.</td>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;">
        - Reafirmação de conhecimentos comuns.<br>
        - Repetição de ideias sem inovação.<br>
        - Fatos sem melhorias significativas.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;"><strong>F - Obsoleto</strong></td>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;">Sem novas ideias; ideias triviais ou altamente clichês.</td>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;">
        - Ideias completamente triviais.<br>
        - Uso excessivo de clichês.<br>
        - Ideias padrão sem originalidade.
      </td>
    </tr>
  </tbody>
</table>

---

## Avaliação de Clareza

<table>
  <thead>
    <tr>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Classificação</th>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Descrição</th>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Exemplos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;"><strong>A - Cristalino</strong></td>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Argumento muito claro e conciso, mantendo um fluxo lógico sem perder o foco principal.</td>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">
        - Estrutura bem organizada.<br>
        - Transições suaves entre ideias.<br>
        - Mensagem principal facilmente identificável.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;"><strong>B - Limpo</strong></td>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;">Argumento bastante claro e conciso, com pequenas otimizações necessárias.</td>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;">
        - Pequenas redundâncias.<br>
        - Algumas frases podem ser simplificadas.<br>
        - Clareza geral mantida com ajustes mínimos.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;"><strong>C - Desajeitado</strong></td>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;">Boas ideias presentes, mas falta concisão e clareza nas soluções propostas.</td>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;">
        - Frases longas e complexas.<br>
        - Conexões entre ideias pouco claras.<br>
        - Necessidade de simplificação do texto.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;"><strong>D - Confuso</strong></td>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;">Escrita bastante confusa, sem clareza nas conexões entre as partes.</td>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;">
        - Falta de coesão entre parágrafos.<br>
        - Ideias mal estruturadas.<br>
        - Dificuldade em seguir o argumento principal.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;"><strong>F - Caótico</strong></td>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;">Não está claro o que está sendo tentado, sem estrutura compreensível.</td>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;">
        - Texto sem lógica aparente.<br>
        - Ideias desconexas.<br>
        - Mensagem completamente obscura.
      </td>
    </tr>
  </tbody>
</table>

---

## Avaliação de Prosa

<table>
  <thead>
    <tr>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Classificação</th>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Descrição</th>
      <th style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Exemplos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;"><strong>A - Inspirado</strong></td>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">Prosa clara, fresca e distintiva, livre de clichês.</td>
      <td style="background-color:#FFD700; color:white; padding:8px; border:1px solid #ddd;">
        - Uso de linguagem original.<br>
        - Estilo único.<br>
        - Escrita envolvente e criativa.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;"><strong>B - Distintivo</strong></td>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;">Escrita forte que não utiliza clichês significativos.</td>
      <td style="background-color:#FFEB3B; color:black; padding:8px; border:1px solid #ddd;">
        - Variação na estrutura das frases.<br>
        - Linguagem precisa.<br>
        - Estilo consistente e interessante.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;"><strong>C - Padrão</strong></td>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;">Prosa decente, mas sem estilo distintivo e/ou com uso excessivo de clichês.</td>
      <td style="background-color:#FFFACD; color:black; padding:8px; border:1px solid #ddd;">
        - Uso frequente de frases padrão.<br>
        - Falta de originalidade no estilo.<br>
        - Escrita funcional.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;"><strong>D - Obsoleto</strong></td>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;">Uso significativo de clichês e/ou linguagem fraca.</td>
      <td style="background-color:#FFA500; color:white; padding:8px; border:1px solid #ddd;">
        - Frases clichês.<br>
        - Linguagem monótona.<br>
        - Falta de vigor na escrita.
      </td>
    </tr>
    <tr>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;"><strong>F - Fraco</strong></td>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;">Fraqueza esmagadora na linguagem e/ou uso de clichês.</td>
      <td style="background-color:#FF6347; color:white; padding:8px; border:1px solid #ddd;">
        - Escrita desmotivada.<br>
        - Clichês excessivos.<br>
        - Linguagem pobre e inexpressiva.
      </td>
    </tr>
  </tbody>
</table>

---

## Recomendações para Melhorar a Classificação

- **Novidade:**
  - Introduzir conceitos inéditos ou abordagens inovadoras.
  - Explorar novas pesquisas ou teorias emergentes.
  - Propor soluções criativas para desafios atuais.
  
- **Clareza:**
  - Eliminar redundâncias e simplificar sentenças.
  - Usar transições claras entre seções.
  - Garantir que o fluxo de ideias seja lógico e fácil de seguir.
  
- **Prosa:**
  - Evitar expressões comuns e clichês.
  - Desenvolver uma voz única e distintiva.
  - Variar a estrutura das sentenças para dinamizar a leitura.

---

## Resumo

Este guia fornece uma visão clara das escalas de classificação para avaliar a qualidade de textos, facilitando a identificação de áreas de melhoria e promovendo a escrita eficaz e inovadora.

---

# Licença

Este projeto está licenciado sob os termos da licença [MIT](https://opensource.org/licenses/MIT).

# Contato

Para mais informações ou sugestões, entre em contato com [seu-email@dominio.com](mailto:seu-email@dominio.com).

# Contribuições

Contribuições são bem-vindas! Por favor, abra uma _issue_ ou envie um _pull request_.

# Fim do README

---

**Observações Importantes:**

1. **Uso de Tabelas HTML:** As tabelas foram criadas utilizando HTML para garantir que toda a célula seja colorida, evitando problemas de renderização no Obsidian.

2. **Estilos de Cores:** As cores seguem um padrão degradê, onde os níveis mais altos se aproximam dos tons amarelos quase-dourados, facilitando a identificação visual das classificações.

3. **Compatibilidade com Obsidian:** Ao utilizar tabelas HTML dentro do markdown, assegure-se de que o Obsidian está configurado para renderizar HTML dentro dos arquivos markdown. Isso geralmente está habilitado por padrão, mas pode ser verificado nas configurações do Obsidian.

4. **Evitar Mistura de Markdown e HTML em Tabelas:** Para evitar a criação de colunas em branco ou cabeçalhos faltantes, todas as tabelas foram feitas exclusivamente em HTML, sem misturar com a sintaxe de tabelas markdown.

5. **Testar Antes de Utilizar:** Recomenda-se visualizar o README no Obsidian antes de finalizar, garantindo que as tabelas estão sendo exibidas corretamente conforme desejado.

Se precisar de mais ajustes ou tiver outras preferências de formatação, estou à disposição para ajudar!