# Rainwater-harvesting-feasibility
Este é o código usado no meu doutorado para avaliar a viabilidade de sistemas de aproveitamento de água pluvial considerando incertezas profundas
O programa considera os seguintes passos, que são divididos em códigos:
  - Código 1: São criados 1000 cenários de regime pluviométrico empregando a análise bootstrapping.
        - Dados de entrada: arquivo csv de uma série histórica diária de precipitação.  
  - Código 2: São criados 1000 cenários de parâmetros de incertezas profundas (DUs: tarifa de água, taxa de desconto e custos operacionais) por meio do método LHS.
        - Dados de entrada: limites mínimos e máximos para cada DU.
  - Código 3: A partir dos dados de entrada os reservatórios são dimensionados e são calculados indicadores de performance dos sistemas (Demanda Atendida (DA), Confiabilidade (CON), Volume Aproveitado (VA), Valor Presente Líquido (VPL), Valor Presente Líquido por Volume (VPLV), Índice Custo Benefício (IBC)).
         -1) Simulação contínua do balanço de massa diária para cada volume de armazenamento definido como dado de entrada;
         -2) Determinação da DA, CON, VA e determinação do volume ideal;
         -3) Avaliação econômica;
         -4) Determinação do VPL, VPLV e IBC;
         -5) Determinação do volume que apresenta o valor máximo de cada indicador assim como os demais indicadores para cada volume.
         - Dados de entrada: arquivos gerados com os Códigos 1 e 2, arquivo csv com informações de demanda, preços de reservatório, estrutura tarifária, parâmetros de dimensionamento e econômicos.
         -
