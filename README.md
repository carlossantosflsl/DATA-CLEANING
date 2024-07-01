# LIMPEZADADOSCOVID
Apenas uma demonstração simples de limpeza de BigData 
Neste exeplo realizei a ultilização da biblioteca Pandas para a realização de limpeza de um dataset
Iniciei importando o pandas e apelidando ele de pd, para facilitar a utilização ao longo do processo 
Criei uma variavel para atribuição de um DataFrame, utilizei a função "read" o arquivo "csv" e chamei o arquivo para a leitura 
utilizei a função head() para exibição. Não utilizei parâmetros, para que aparecesse o padrão, que é 5. Iniciando a indexação em 0 
Após visualizar o index(5) do nosso data, apliquei a função isnull, para que devolvesse os valores ausentes dos dados
Valores ausente são prejudiciais para análise de dados
E ao aplicar a função isnull, também apliquei a função sum, para que retornasse os valores ausente somados. 
Após a visualização desses valores ausentes, comecei uma limpeza entendendo os meios que não alterariam a integridade do meus dados 
Escolhi alterar os valores ausentes com as strings "Desconhecido" e "Não informado" para que ao aplicar pudesse ter uma indicação que as informações daquele atributo não possui as informações necessárias para uma análise precisa 
E com isso, conseguiremos realizar uma análise mais precisa com os valores informados. 
Apliquei os comendos necessários para alteração. utilizando a função fillna, que é preencher. E informei as strings que deveriam ocupar os lugares dos valores ausentes 
Após isso, solicitei que a função isnull retornasse, para que pudesse haver a visualização da ausencia de valores nulos, entendendo que os dados estão limpos para análise. 
