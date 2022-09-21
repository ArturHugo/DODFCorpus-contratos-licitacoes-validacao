# DODFCorpus - contratos e licitações: métricas de concordância

Universidade de Brasília

Departamento de Ciência da Computação

CIC0269 - Processamento de Linguagem Natural - 2022/1

Aluno: Artur Hugo C. Pereira

Professor: Vinícius R. P. Borges

Esse projeto faz uso do Batch de Validação do corpus de contratos e licitações do Diário Oficial do Distrito Federal, anotado manualmente e desenvolvido pelo projeto de pesquisa [KnEDLe](http://nido.unb.br/). As anotações pré-processadas desse batch estão presentes no arquivo DODFCorpus\_contratos\_licitacoes\_concordancia.csv.

O código fonte do projeto que faz o processamento das anotações para extrair métricas de concordância está disponível no notebook agreement\_metrics.ipynb. Ao final da execução do código, o arquivo df\_with\_metrics.csv é gerado, consistindo na mesmo estrutura do csv original, mas contendo colunas adicionais para cada métrica de concordância estrutural calculada.

O arquivo metrics\_per\_type.json apresenta uma relação dos valores médios e desvios padrão das métricas para cada tipo de entidade. O arquivo annotations\_per\_type.json apresenta uma relação no número de anotações feitas para cada tipo de entidade.

Uma redação mais detalhada sobre o processo de validação do corpus com detalhes da metodologia e considerações finais está disponível no relatório em formato de artigo, paper.pdf.
