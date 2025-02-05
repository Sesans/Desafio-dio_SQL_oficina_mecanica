# Desafio-dio_SQL_Oficina_mecanica
## Esquema conceitual oficina mecânica
Neste desafio eu criei um esquema conceitual que abrange um sistema que irá gerenciar e controlar a criação de ordens de serviço realizadas pela empresa.

**Dada a seguinte narrativa:**

    Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas.
	Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
	A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão de obra.
	O valor de cada peça também irá compor a OS. O cliente autoriza a execução dos serviços.
	A mesma equipe avalia e executa os serviços.
	Os mecânicos possuem código, nome, endereço e especialidade.
	Cada OS possui: n°, data de emissão, valor, status e uma data para a conclusão dos trabalhos.
	Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS.
	Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.
