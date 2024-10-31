# EnterConnection

### Descrição do Projeto
O EnterConnection é um projeto em desenvolvimento voltado para o uso de dados de vendas de um supermercado para identificar as empresas com melhor desempenho. A partir desses dados, o sistema classifica as empresas em "Boas" ou "Ruins" com base em uma média de avaliação e fornece visualizações e operações interativas para manipulação de dados. Esta é uma versão inicial (Beta) e ainda será aprimorada para sua versão final.

- **API de Dados**: [Supermarket Sales Dataset no Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales/data)
- **Pitch do Projeto**: [Link para o vídeo](https://youtu.be/e_yeYsXnbNc)
- **Documentação Completa**: [Link para o OneDrive](https://onedrive.live.com/edit.aspx?resid=442b95dc06c47f3e!sc4435c51-b76f-4e00-98c6-38c4443bf086&cid=442b95dc06c47f3e&ct=1716154271228&wdOrigin=OFFICECOM-HWA.MAIN.EDGEWORTH&wdPreviousSessionSrc=HarmonyDesktop&wdPreviousSession=7e1b0caf-d4fa-45c8-8cc7-f5df6f2187d8)

---

### Estrutura do Código e Funcionalidades

Abaixo, explicamos as principais seções e operações do código:

1. **Bloco 1**: Importação das Bibliotecas  
   Contém as importações das bibliotecas e ferramentas necessárias para processamento e visualização de dados.

2. **Bloco 2**: Leitura e Verificação do Arquivo  
   Realiza a leitura do arquivo de dados e verifica se o conteúdo está correto para o processamento.

3. **Bloco 3**: Análise das Colunas  
   Exibe e seleciona as colunas que serão utilizadas na análise e processamento dos dados.

4. **Bloco 4**: Seleção de Colunas Relevantes  
   Seleciona as colunas "City", "Total" e "Rating" para análise, que contêm informações de localização, valor total de vendas e classificação.

5. **Bloco 5**: Cálculo da Média  
   Calcula a média de classificação de empresas (atualmente 6,97) para basear a separação entre "Boas" e "Ruins".

6. **Bloco 6**: Classificação de Empresas  
   Compara a classificação de cada empresa com a média e classifica como "Boa" ou "Ruim" conforme o resultado.

7. **Bloco 7**: Visualização de Dados com Gráficos  
   Gera gráficos para visualizar a distribuição e desempenho das empresas, com destaque para as empresas "Boas" e "Ruins".

8. **Bloco 8**: Adição de Novas Empresas e Validação  
   Permite adicionar novas empresas ao conjunto de dados, validando as entradas do usuário para manter a integridade dos dados.

9. **Bloco 9**: Manipulação e Visualização de Dados  
   Fornece operações interativas para manipular e visualizar dados das empresas, com validação de entradas e gráficos atualizados.

10. **Bloco 10**: Remoção de Empresas  
    Implementa a funcionalidade para remover empresas do DataFrame.

11. **Bloco 11**: Menu Interativo para Adição/Remoção  
    Um menu interativo que permite ao usuário adicionar ou remover empresas do DataFrame conforme necessário.

12. **Bloco 12**: Recalculo da Média e Reclassificação  
    Após adições ou remoções, recalcula a média de avaliação e reclassifica as empresas para refletir as mudanças.

13. **Bloco 13**: Classificação com Base na Média Atualizada  
    Classifica novamente as empresas em "Boas" ou "Ruins" com base na média atualizada, se necessário.

14. **Bloco 14**: Execução do Fluxo Principal  
    Contém a linha de código que executa o fluxo principal de operações sobre o DataFrame.

---

### Aplicação de Machine Learning / IA

Este projeto utiliza conceitos de Machine Learning/IA na análise e tratamento de dados para dinamizar a compreensão de desempenho das empresas. A partir de técnicas de tratamento de dados, a IA ajuda a identificar padrões que indicam as melhores e piores avaliações de clientes, otimizando estratégias para melhorar o desempenho e maximizar ganhos. Futuras melhorias podem incluir a implementação de modelos preditivos para insights mais avançados.

---

### Reflexão profunda 

Este trabalho aborda uma temática muito relevante, porém, devido a mudanças ocorridas ao longo do projeto — incluindo a saída de alguns integrantes do grupo —, acabou divergindo um pouco do conceito inicialmente planejado. Essas alterações trouxeram desafios que impactaram o foco original. No entanto, apesar dos obstáculos, conseguimos entregar uma versão funcional e alinhada com as expectativas.

Ainda há alguns aspectos que podem ser aprimorados, como uma organização mais estruturada no código. Futuramente, a integração de uma API do ChatGPT também está nos planos, o que permitiria automatizar certas interações e oferecer ainda mais valor às empresas que utilizarem o sistema.
