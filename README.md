# Conceitos @ DDD

## Estrutura 

* "Projeto".Application: Class Library aonde ficam meus aquivos de persistência/repositório e interface;
* "Projeto".Domain: Class Library aonde se encontram meus "Models/Entities";
* "Projeto".Infra.Data: Class Library responsável pelo mapeamento das models (mapping/fluentAPI);
* "Projeto".MVC: Projeto MVC padrão, porém sem as Models e Repositórios diretamente explícitos;
