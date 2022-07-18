# Rainwater-harvesting-feasibility
Este é o código usado no meu doutorado para avaliar a viabilidade de sistemas de aproveitamento de água pluvial considerando incertezas profundas
O programa considera os seguintes passos, que são divididos em códigos:
  1) São criados 1000 cenários de regime pluviométrico a partir de uma série histórica diária de precipitação empregando a análise bootstrapping 
  2) São criados 1000 cenários de parâmetros de incertezas profundas (DUs: tarifa de água, taxa de desconto e custos operacionais) por meio do método LHS
