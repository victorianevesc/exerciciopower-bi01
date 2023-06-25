Exercícios Power Query
- Importante: lembre de sempre fazer as edições pelo Power Query e não pelo
Excel. Isso porque se for uma planilha que a empresa baixa de um sistema, ela
sempre vai vir no mesmo formato, então a ideia é sempre editar pelo Power
Query para deixar automático pra quando entrarem novas informações.
- Repare que na planilha original, além da tabela tem um texto escrito (no nosso
cenário, a planilha veio assim do sistema). Então você vai precisar editar a tabela
pra só ter as informações que interessam, ou seja, a tabela sem esse texto que
aparece na primeira linha da planilha.
1) Importe a tabela Base Funcionários - Ativos, que é a tabela com os colaboradores
atuais da empresa. Crie uma coluna para calcular o ‘Salário com Imposto’, sendo o
imposto de 60% do salário. Então se a pessoa ganha R$10.000, por exemplo, o salário
que a empresa paga, contando com o imposto, será de R$16.000
2) Crie uma coluna de ‘Gasto Salarial’, somando as colunas de Salário com Imposto, VR
e VT
3) Crie uma Coluna com a avaliação do funcionário de acordo com a nota dele:
■ Maior ou igual a 7: Boa
■ Maior ou igual a 5 e menor que 7: Razoável
■ Abaixo de 5: Ruim
4) Crie uma coluna para calcular a idade do funcionário e outra para calcular o tempo
de empresa do funcionário (em anos)
5) Crie uma coluna com a cidade do funcionário - extraindo a cidade do endereço
completo
Agora feche e Carregue a Tabela do Power Query para o Power BI.
Em seguida, acrescente um novo funcionário na planilha do Excel:
- Cadastro Funcionário: FC235
- Nome: João Pinheiro
- Gênero: Masculino
- Nascimento: 19/08/1992
- Endereço: R. Visc. de Pirajá, 136 - Ipanema, Rio de Janeiro - RJ, 22410-000
- Data de Contratação: 10/10/2022
- Salário: R$8500
- VR (Vale Refeição): R$600
- VT (Vale Transporte): R$160
- Cargo e Área: Analista - Comercial
- Nota: 7,5
6) Atualize o Power BI e corrija o erro que vai dar
7) Agora imagine que a empresa te enviou a BaseFuncionarios - Desligados com os
funcionários que já saíram da empresa. O objetivo é você juntar essa tabela com a
tabela de funcionários ativos, na mesma base de dados.
8) Imagine que alguém renomeou a aba do Excel de ‘BaseFuncionarios’ para
‘Funcionarios Ativos’ - Volte na planilha e renomeie para simular esse cenário. Em
seguida, atualize o Power BI e corrija o erro que deu.
