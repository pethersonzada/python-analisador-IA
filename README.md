## Previsão de Score de Crédito com IA

Este projeto utiliza algoritmos de aprendizado de máquina, como Random Forest e K-Nearest Neighbors, para prever o score de crédito de clientes com base em variáveis como profissão, mix de crédito e comportamento de pagamento.

### Bibliotecas usadas:

    pandas: Manipulação e análise de dados.
    sklearn: Ferramentas para aprendizado de máquina, incluindo codificação de dados, divisão de treino/teste, classificadores e avaliação de modelos.

### Como usar:

Instale as dependências necessárias:

    pip install pandas scikit-learn

Certifique-se de ter os arquivos CSV (clientes.csv e novos_clientes.csv) com os dados corretos.
Execute o script para treinar os modelos e fazer previsões de score de crédito.

### Etapas do Processo:

 * Preparação dos dados:
    
        Os dados categóricos de profissão, mix_credito e comportamento_pagamento são convertidos para valores numéricos usando LabelEncoder.
        
* Treinamento dos Modelos:

        Dois modelos são treinados: Random Forest e K-Nearest Neighbors.
        
* Avaliação dos Modelos:

        A acurácia de cada modelo é comparada usando o conjunto de teste.
        
* Previsão de Novos Scores:

        O modelo selecionado faz previsões para novos clientes com base em dados fornecidos.
        
### Comentário!

Este código foi comentado por mim durante todo o processo de desenvolvimento. Caso algum erro seja encontrado, peço desculpas, pois os comentários refletem apenas minha linha de raciocínio, com o objetivo de tornar o código o mais didático possível.

## Aviso de Direitos Autorais

Este código foi desenvolvido por Miguel Petherson e está protegido por direitos autorais. Ele não possui uma licença aberta, o que significa que:  

- **Você não tem permissão para copiar, modificar ou redistribuir este código sem autorização prévia do autor.**
- Caso queira usar este código para qualquer finalidade, entre em contato por email - pethersonzada@gmail.com  

Por favor, respeite os direitos autorais e o trabalho investido neste projeto.  
Agradeço pela compreensão! 😊

