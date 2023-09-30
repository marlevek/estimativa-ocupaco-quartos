# Marketing Bancário
Os dados estão relacionados com campanhas de marketing direto (chamadas telefônicas) de uma instituição bancária portuguesa. O objetivo da classificação é prever se o cliente irá subscrever um depósito a prazo (variável y).

Informações Adicionais
Os dados estão relacionados com campanhas de marketing direto de uma instituição bancária portuguesa. As campanhas de marketing foram baseadas em telefonemas. Muitas vezes, era necessário mais de um contato com o mesmo cliente, a fim de acessar se o produto (depósito bancário a prazo) estaria ('sim') ou não ('não') inscrito. 
Há quatro conjuntos de dados: 
1) banco-adicional-cheio.csv com todos os exemplos (41188) e 20 entradas, ordenados por data (de maio de 2008 a novembro de 2010), muito próximos aos dados analisados em [Moro et al., 2014]
2) banco-adicional.csv com 10% dos exemplos (4119), selecionados aleatoriamente de 1), e 20 entradas.
3) banco-cheio.csv com todos os exemplos e 17 entradas, ordenado por data (versão mais antiga deste conjunto de dados com menos entradas). 
4) banco.csv com 10% dos exemplos e 17 entradas, selecionados aleatoriamente entre 3 (versão mais antiga desse conjunto de dados com menos entradas). 
Os menores conjuntos de dados são fornecidos para testar algoritmos de aprendizado de máquina mais exigentes computacionalmente (por exemplo, SVM). 
O objetivo da classificação é prever se o cliente irá subscrever (sim/não) um depósito a prazo (variável y).
Informações adicionais sobre variáveis

## Variáveis de entrada: 

## dados do cliente bancário:
1.	idade (numérica) 
2.	emprego: tipo de emprego (categórico: "admin.", "desconhecido", "desempregado", "gerência", "empregada doméstica", "empresário", "estudante", "colarinho azul", "autônomo", "aposentado", "técnico", "serviços") 
3.	conjugal: estado civil (categórico: "casado", "divorciado", "solteiro"; nota: "divorciado" significa divorciado ou viúvo)
4.	educação (categórica: "desconhecido", "secundário", "primário", "terciário") 
5.	inadimplência: tem crédito inadimplente? (binário: "sim", "não") 
6.	saldo: saldo médio anual, em euros (numérico)
7.	habitação: tem crédito habitação? (binário: "sim", "não") 
8.	empréstimo: tem empréstimo pessoal? (binário: "sim", "não") 
9.	#relacionado com o último contato da campanha atual:
contato: contato tipo de comunicação (categórico: "desconhecido", "telefone", "celular") 
10.	dia: último contato dia do mês (numérico) 
11.	mês: último contato mês do ano (categórico: "jan",  "fev",  "mar", ...,  "nov", "dez") 
12.	duração: duração do último contato, em segundos (numérico) # outros atributos: 
13.	campanha: número de contatos realizados durante esta campanha e para este cliente (numérico, inclui último contato) 
14.	pdays: número de dias que se passaram após o cliente ter sido contatado pela última vez de uma campanha anterior (numérico, -1 significa que o cliente não foi contatado anteriormente) 
15.	anterior: número de contatos realizados antes desta campanha e para este cliente (numérico) 
16.	poutcome: resultado da campanha de marketing anterior (categórico: "desconhecido", "outro", "fracasso", "sucesso") 

## ariável de saída (alvo desejado):  
17.	Y - O cliente subscreveu um depósito a prazo? (binário: "sim", "não")

Link: <a href:'https://archive.ics.uci.edu/dataset/222/bank+marketing'>Bank Marketing - UCI Machine Learning Repository</a>

