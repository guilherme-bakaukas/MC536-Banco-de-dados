# Lab06 - Artigo de Dataset Público

# Aluno
* `217332`: `Guilherme Tezoli Bakaukas`

# Análise do Artigo `PolRoute-DS: um Dataset de Dados Criminais para Geração de Rotas de Patrulhamento Policial`

| campo | valor |
|------------|----------------------------------------|
| referência | `SÁ, B.; MULLER, G.; BANNI, M.; SANTOS, W.; LAGE, M.; ROSSETI, I.; FROTA, Y.; OLIVEIRA, D. PolRoute-DS: um Dataset de Dados Criminais para Geração de Rotas de Patrulhamento Policial. SBBD-DSW, 2021. Disponível em: <https://drive.google.com/file/d/10Q_T1TANC5BtEBpPexsTv7-gfOLva5X2/view>. Acesso em 30 de set de 2021.` |
| link       | `https://drive.google.com/file/d/10Q_T1TANC5BtEBpPexsTv7-gfOLva5X2/view` |
| dataset | `https://osf.io/mxrgu/` |
| formato | `csv` |

## Resumo

> O artigo apresenta um dataset que contem dados sobre a criminalidade em São Paulo. Sua organização é centralizada na tabela de crimes, nela há informações sobre a quantidade de cada tipo de crime em determinada localidade e intervalo de tempo. Dentre as categorias de crimes foram apresentados Latrocínio, Feminicídio, Furto de celular, etc. Já a localização é disponibilizada através de tabelas de segmentos, distritos, bairros, vértices e zonas. Sendo que a referência utilizada na tabela de crimes é direcionada apenas ao segmento, pelo qual é possível acessar as demais informações citadas. Vale a pena citar que esse método representa as ruas através de segmentos entre os vértices da cidade. Assim, é possível ter acesso ao cenário urbano da cidade. Portanto, com essas informações é possível prover uma melhor análise do contexto de criminalidade do local.

## Perguntas de pesquisa/análises

> Assim como citado no artigo, é possível contabilizar a quantidade de crimes cometidos agrupados por categoria. Assim, é possível quantificar a ocorrência de cada tipo de crime na cidade. Uma outra análise interessante seria mapear o crime mais típico de cada bairro. Ou seja, coletar o crime mais recorrente em cada bairro. Para uma análise temporal, é possível gerar indicadores de progressão de cada tipo de crime. Para isso, um gráfico pode ser gerado, assumindo intervalos de tempo iguais e relacionando com a quantidade de cada crime nesse respectivo intervalo.

> As alternativas de análise podem gerar um grande impacto na mobilização policial. Ao identificar os focos de cada tipo de crime, é possível distribuir e gerenciar os esforços de maneira direcionada. Com informações sobre a progressão, torna-se viável criar uma predição para o cenário futuro da criminalidade na cidade, permitindo uma melhor preparação. 

## Trabalhos relacionados

> O dataset em questão tem grande impacto na determinação de rotas policiais. Isto é, foi criado um índice para cada segmento cujo valor mensurava a criminalidade daquele local. Esse cálculo leva em conta quantidade da cada crime e lhe atribui um peso relativo ao nível de ameaça a vida. Assim, ao analisar os maiores índices de cada zona, se distribui as  forças policiais a fim de mitigar as ocorrências. Além desse uso, o artigo também contabiliza a quantidade de crimes agrupados por categoria e apresenta os resultados em um formato de gráfico.
