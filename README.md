# techlead-test

Segue descrição de projeto para entrega como parte do processo seletivo das vagas de Tech Lead da VMBears.
O objetivo é avaliar a fluência e qualidade do código escrito na tecnologia JAVA.

# Pré-requisitos

* O código da aplicação deve estar hospedado no github;
* As dependências maven devem estar disponíveis em repositórios públicos;
* Imagem docker deve ser compartilhada por meio do dockerhub;
* Utilize Spring Boot;
* Utilizar repositório de dados H2;
* Utilize Maven;

# Teste

Construa um microserviço "RESTFul" que :

* Implemente as operações de inclusão, seleção, atualização e exclusão de especialidade por meio de endpoints;
* Descreve atributos fictícios para entidade especialidade;
* Implemente as operações de inclusão, seleção, atualização e exclusão de hospital por meio de endpoints;
* Descreve atributos fictícios para entidade hospital;
* Implemente as operações de inclusão, seleção, atualização e exclusão de médicos por meio de endpoints;
* Descreve atributos fictícios para entidade médico, e crie um relacionamento do tipo N-N com hospitais;
* Descreva na relação entre o médico e o hospital um tipo de especialidade;
* Crie uma operação para associar médicos a hospitais, que valide:
** Um médico deve estar relacionado no máximo a 5 hospitais;
** Um médico pode apenas estar relaciona a um hospital com uma especialidade;
* Crie uma operação periódica, que escreva no log da aplicação a cada hora, se o hospital possui ao menos um médico por especialidade disponível;

# Itens opcionais

Escreve o código da aplicação seguindo:

* Clean Architecture;
* Entregar imagem docker em repositório público no dockerhub;
* Escreva testes automatizados;
