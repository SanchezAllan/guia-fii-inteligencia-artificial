[Fundos_de_Investimentos_Imobiliarios.pdf](https://github.com/user-attachments/files/26390439/Fundos_de_Investimentos_Imobiliarios.pdf)# guia-fii-inteligencia-artificial
o objetivo é utilizar o NotebookLM para analisar o mercado de Fundos Imobiliários em 2026, focando em entender indicadores como Dividend Yield, P/VP e vacância, facilitando a tomada de decisão para investidores iniciantes.

## 🛠️ Engenharia de Prompts

Nesta etapa, realizei testes para validar a precisão da IA:

1. **Prompt de Análise Comparativa:**
   - **Pergunta 1:** Com base nos relatórios gerenciais que anexei, KNCR11 e HGLG11 compare o Dividend Yield e o P/VP dos fundos de tijolo e de papel. Qual deles parece estar mais barato no momento?"
   ** Pergunta de ajustes:** Com base nos relatórios gerenciais que anexei, KNCR11 e HGLG11 compare o Dividend Yield e o P/VP dos fundos de tijolo e de papel. Qual deles parece estar mais barato no momento?
   - **Resultado: Inicial** na pergunta inicial a IA não conseguiu responder.
   - **Resultado ajuste:** A ia entregou o resultado esperado com explicações dos motivos e citando fontes. 
   - **Cicatriz:**  Após a realização da perfunta incial da IA realizei um ajuste na pergunta, fazendo com que ela entregasse o esperado. 

2. **Prompt de Simulação de Renda:**
   - **Pergunta:** "Se eu investir R$ 10.000,00 divididos igualmente entre os fundos citados nos documentos, qual seria minha estimativa de renda mensal aproximada baseada nos últimos rendimentos informados?"
   - **Resultado:** A IA calculou o valor, e deu sugestão do que fazer com o dinheiro que sobre após divisão igualitária.
   - **Cicatriz:** Tive que adicionar um novo prompt perguntando sobre os custos extras de investir na Bolsa.
  
3. **Prompt de "Persona" (Didático)** 

 **Pergunta 1:** "Explique para um aluno do ensino médio, usando uma metáfora sobre aluguel de casas, por que os FIIs de tijolo são diferentes dos FIIs de papel."

**Resultado: Inicial:** A IA apresenta argumentos simples, de aluguel de imóvel e emprestismo de dinheiro, mas sem muita criatividade. 

  - **Cicatriz:** Achei a explicação justa mas sem muita criatividade para um aluno de ensino médio, e senti falta de um maior aprofundamento sobre fiis de papel. Após pedir explicações adicionais a IA entregou resultado além do esperado. 



  ## 📚 Curadoria de Fontes
Para este estudo, foram utilizados os seguintes documentos como base de conhecimento para a IA:
1. **Guia de FIIs da B3**: Manual oficial sobre o funcionamento dos fundos.
https://www.b3.com.br/pt_br/produtos-e-servicos/negociacao/renda-variavel/fundos-de-investimento-imobiliario-fii.htm
2. **Relatório Gerencial HGLG11**: Fundo de logística (Tijolo).[hglg.pdf](https://github.com/user-attachments/files/26390449/hglg.pdf)
3. **Relatório Gerencial KNCR11 (Mês/Ano)**: Fundo de recebíveis imobiliários (Papel).[kncr.pdf](https://github.com/user-attachments/files/26390448/kncr.pdf)
4. **Vídeo**: COMO MONTAR UMA CARTEIRA DE FUNDOS IMOBILIÁRIOS (COM R$1.000) ( O primo Rico) 
https://www.youtube.com/watch?v=gOuYvRw5kE4
5. **Vídeo**: Aula sobre Fundos Imobiliários (do Zero para Iniciantes) ( primo pobre)
https://www.youtube.com/watch?v=z3fTzc0q10M
6. [Guia de Fundos de Investimento Imobiliários.pdf](https://github.com/user-attachments/files/26390447/Guia.de.Fundos.de.Investimento.Imobiliarios.pdf)
7. [E-book-Sobre-Fundos-de-Investimentos-Imobiliários-2.0.pdf](https://github.com/user-attachments/files/26390445/E-book-Sobre-Fundos-de-Investimentos-Imobiliarios-2.0.pdf)
8. [Ebook-viver-de-renda-com-fundos-imobiliarios-FIIs.pdf](https://github.com/user-attachments/files/26390443/Ebook-viver-de-renda-com-fundos-imobiliarios-FIIs.pdf)


## Link NotebookLM com a atividade
https://notebooklm.google.com/notebook/e0e9cf03-35b5-4704-91e4-361e0bbbe9f7
