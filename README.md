# Análise de Sentimentos com Language Studio no Azure AI

## Descrição do Projeto
Este projeto visa demonstrar o uso da ferramenta Análise de Sentimentos do Language Studio no Azure AI para classificar o sentimento de diversas sentenças. A análise de sentimentos é uma técnica de processamento de linguagem natural (NLP) que identifica a polaridade (positiva, negativa ou neutra) das emoções em um texto.

## Objetivo
O objetivo deste repositório é documentar o processo de utilização do Azure AI Language Studio para realizar a análise de sentimentos de um conjunto de frases. Durante o processo, foram feitas algumas observações sobre o comportamento da ferramenta e os resultados obtidos.

## Estrutura do Repositório
Este repositório contém as seguintes pastas e arquivos:

* inputs/: Contém o arquivo de texto com as sentenças a serem analisadas.

## Resultados da Análise de Sentimentos

Aqui estão os resultados da análise realizada com o **Azure AI Language Studio**:

| Sentença                                   | Sentimento |
|--------------------------------------------|------------|
| O atendimento no restaurante foi excelente, os garçons são muito atenciosos! | Positivo   |
| Meu pedido veio certinho e dentro do prazo, estou muito satisfeito!          | Positivo   |
| O quarto do hotel estava sujo e com um cheiro estranho. | Negativo     |
| A comida estava fria e sem sabor, não gostei da experiência.    | Negativo   |

##  Insights
### Análise dos Resultados
**Sentenças Positivas:**
- A IA identificou corretamente frases que expressam satisfação, como elogios ao atendimento e à entrega do pedido no prazo. Isso mostra que o modelo reconhece palavras-chave como "excelente", "muito atenciosos", "satisfeito" e entende que são indicadores de uma experiência positiva.

**Sentenças Negativas:**
- O modelo detectou corretamente as reclamações sobre o hotel e a comida. Termos como "sujo", "cheiro estranho", "fria", "sem sabor" e "não gostei" são fortes indicadores de insatisfação, o que reforça a precisão da ferramenta na análise de sentimentos negativos.

# Possibilidades de Aplicação
- **Análise de Feedback de Clientes:** Empresas podem usar a análise de sentimentos para entender como seus clientes estão se sentindo em relação aos serviços ou produtos oferecidos.
- **Monitoramento de Redes Sociais:** Identificar rapidamente menções positivas ou negativas em plataformas como Twitter e Facebook.
- **Análise de Comentários:** Avaliar os sentimentos em comentários de usuários em blogs, fóruns e avaliações de produtos.
  
## Prints do Processo
### Sentença positiva:
 <img src="https://ik.imagekit.io/ajt99blle/senttencas/positivo1.jpg?updatedAt=1741469656388" width="700"/> 

 ### Sentença positiva:
 <img src="https://ik.imagekit.io/ajt99blle/senttencas/positivo2.jpg?updatedAt=1741469656583" width="700"/> 

 ### Sentença negativa:
 <img src="https://ik.imagekit.io/ajt99blle/senttencas/negativo1.jpg?updatedAt=1741469656510" width="700"/> 

### Sentença negativa:
 <img src="https://ik.imagekit.io/ajt99blle/senttencas/negativo2.jpg?updatedAt=1741469656483" width="700"/> 
 
# Conclusão
O projeto demonstrou como usar a ferramenta de análise de sentimentos do Azure Language Studio para processar e analisar dados textuais. A ferramenta é eficaz para classificar sentimentos, e pode ser aplicada em diversas áreas como análise de feedback, monitoramento de redes sociais, suporte ao cliente e avaliações de produtos e serviços.
