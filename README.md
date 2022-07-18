# Rainwater-harvesting-feasibility

This is the code used in my PhD to assess rainwater harvesting systems feasibility considering deep uncertainties.
The program considers the following steps, which are divided into codes:
  - Code 1: 1000 rainfall regime scenarios are created using bootstrapping analysis.
    * Input data: csv file of a historical rainfall series
  - Code 2: 1000 scenarios of deep uncertainty parameters - DUs (discount rate, tariff and operating costs) are created using the LHS method.
    * Input data: minimum and maximum limits for each DU.
  - Code 3: Based on the input data, the reservoirs are dimensioned and the behavior of the systems is evaluated through technical (Satisfied Demand - SD, Reliability - REL and Rainwater Consumed - RH) and economic indicators (Net Present Value - NPV, Net Present Value Volume - NPVV and Benefit Cost Rate - BCR) in the context of uncertainties.
    * Input data: input files generated with codes 1 and 2, files with demand information, reservation prices, tariff structure, sizing and economic parameters.
    1) Continuous simulation of the daily mass balance for each storage volume defined as input;
    2) Determination of SD, CON, RH and determination of the ideal volume;
    3) Economic evaluation;
    4) Determination of NPV, NPVV and BCR;
    5) Determination of the volume that presents the maximum value of each indicator as well as the other indicators for each volume.




Este é o código usado no meu doutorado para avaliar a viabilidade de sistemas de aproveitamento de água pluvial considerando incertezas profundas
O programa considera os seguintes passos, que são divididos em códigos:
  - Código 1: São criados 1000 cenários de regime pluviométrico empregando a análise bootstrapping.
    *    Dados de entrada: arquivo csv de uma série histórica diária de precipitação.  
  - Código 2: São criados 1000 cenários de parâmetros de incertezas profundas (DUs: tarifa de água, taxa de desconto e custos operacionais) por meio do método LHS.
    *    Dados de entrada: limites mínimos e máximos para cada DU.
  - Código 3: A partir dos dados de entrada os reservatórios são dimensionados e é efetuada a avaliação do comportamento dos sistemas por meio de indicadores técnicos (Demanda Atendida - SD, Confiabilidade - REL and Água Aproveitada - RH) e econômicos (Valor Presente Líquido - NPV, Valor Presente Líquido por volume - NPVV and Índice Custo Benefício - BCR) no contexto de incertezas.
    *    Dados de entrada: arquivos gerados com os Códigos 1 e 2, arquivo csv com informações de demanda, preços de reservatório, estrutura tarifária, parâmetros de dimensionamento e econômicos.
    1) Simulação contínua do balanço de massa diária para cada volume de armazenamento definido como dado de entrada;
    2) Determinação da DA, CON, VA e determinação do volume ideal;
    3) Avaliação econômica;
    4) Determinação do VPL, VPLV e IBC;
    5) Determinação do volume que apresenta o valor máximo de cada indicador assim como os demais indicadores para cada volume.
