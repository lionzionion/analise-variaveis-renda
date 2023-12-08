# analise-variaveis-renda

## Análise de Perfil de Renda - Módulo 10 Atividade 1
Este repositório contém uma análise detalhada do perfil de renda de clientes de uma instituição financeira, com o objetivo de construir um modelo preditivo para a renda com base em variáveis disponíveis no banco de dados.

## Arquivo de Dados
O arquivo previsao_de_renda.csv foi utilizado para conduzir esta análise. Ele contém informações sobre clientes, incluindo variáveis como idade, posse de veículo, posse de imóvel, quantidade de filhos, tempo de emprego, entre outras.

## Estrutura de Correlação
O primeiro passo foi avaliar a estrutura de correlação entre as variáveis quantitativas. O gráfico de matriz de dispersão e a matriz de correlação destacaram padrões interessantes, como inversa relação entre Unnamed: 0 e index, a fraca correlação entre posse de veículo e posse de imóvel, e a relação moderada entre idade, quantidade de filhos e tempo de emprego.

## Scatterplot - Variáveis mais Correlacionadas com Renda
Um scatterplot foi gerado para as duas variáveis mais correlacionadas com a renda: quantidade de pessoas na residência (qt_pessoas_residencia) e tempo de emprego (tempo_emprego). O gráfico revelou concentrações específicas em relação à quantidade de pessoas na residência e ao tempo de emprego, fornecendo insights valiosos.

## Análise de Outliers na Variável Renda
Identificamos outliers na variável renda usando escores Z. O número total de outliers foi 263, indicando rendas significativamente afastadas da maioria dos dados. Um gráfico de regressão foi utilizado para visualizar a distribuição e identificar esses outliers.

## Aplicação do Logaritmo na Variável Renda
A variável renda foi transformada aplicando o logaritmo, resultando em melhorias significativas. O número de outliers foi reduzido para 52, indicando uma distribuição mais suavizada. O boxplot e o gráfico de regressão para a variável logarítmica (log_renda) mostraram uma distribuição mais simétrica e clara.

## Conclusões Pessoais
Na minha opinião, a aplicação do logaritmo melhorou substancialmente a análise, tornando os dados mais adequados para técnicas estatísticas e preditivas. A redução de outliers, melhora na visualização e impacto positivo na análise de regressão destacam a eficácia dessa transformação.

## Uso deste Repositório
Este repositório fornece uma visão abrangente do processo de análise de perfil de renda. Os códigos, visualizações e insights podem ser utilizados como referência para análises semelhantes em outros conjuntos de dados. Certifique-se de ajustar os códigos conforme necessário para atender aos requisitos específicos do seu projeto.

## Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para obter detalhes.
