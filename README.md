Prezado candidato, parabéns por estar na fase final. Segue o pequeno sistema que deve ser implementado. Queremos avaliar a sua capacidade de propor e implementar uma solução utilizando o conceito de micro serviços com PHP ou JAVA. 

# Selecao-dev-2018
Seleção de programador Java e PHP

Autor: Rodrigo Fujioka, Martin Pfifer
Revisores:  José Filho
Equipe de Avaliação:  José Filho, Martin Pfeifer


## Objetivos
Implemente um pequeno sistema para cotistas utilizando o conceito de micro serviços < https://martinfowler.com/articles/microservices.html  http://blog.caelum.com.br/arquitetura-de-microservicos-ou-monolitica />. 
Deve ser realizado fork do projeto disponibilizado no github < https://github.com/publicsoftpb/selecao-dev-publicsoft>, no fork, o arquivo MD deve ser alterado para constar as instruções para execução e configuração. 

O sistema terá o código avaliado bem como a solução que foi proposta.

## Recomendações

- Utilização de Frameworks PHP ou JAVA para criação da API no back-end (Laravel, Symfony, Spring Boot, etc) 
- Utilização de Angular ou React com BootStrap< http://getbootstrap.com /> no front-end. 

Obs: Não se limitando apenas a estes, o candidato tem a liberdade para apresentar outras abordagens desde que seja utilizado PHP ou JAVA no back-end.


## Itens a serem propostos e avaliados

- Padrões de projeto;
- Qualidade do código;
- Organização dos arquivos;
- Criatividade;

Ps:. Lembre-se que a PublicSoft trabalha, em sua maioria com clientes do setor público. 

### Item Obrigatório
- O sistema tem que possuir um controle de acesso/permissões, e toda a parte de autenticação terá que ser feita com JWT <https://jwt.io//> ou OAUTH 2.0 <https://oauth.net//>.

## PROJETO A SER IMPLEMENTADO.

### O sistema deve ter uma interface administrativa que permita operações de gerenciamento de:

1. Usuário
2. Grupo de usuários. ex: (Admin, Financeiro, Candidato)
3. Controle de permissões para acessar os recursos (métdos da api) na aplicação

4. Cadastrar condição para cotista. ex: escolaridade tem que ser pública, renda terá que ser igual ou menor à R$ 1500,00 
4.1 - A etnia e raça tem que ser (parda, negro, indígena).

Obs: As condições cadastradas no painel administrativo ser utilizadas no cadastro do candidato, neste caso terá que deixar customizável.

5. Listarem os candidatos com filtros de nome, cpf, cotista (flag).

6. Analisar a vericidadeveracidade dos dados dos candidatos. 
6.1  - Assim sendo, ao atender as condições exigidas, o candidato receberá uma comprovação de cotista, caso contrário uma declaração de não cotista.

7. Visualizar os arquivos de comprovação de pertencimento a instituição educacional e declaração de renda do candidato

### O sistema deve ter uma interface para ser utilizada pelos usuários no qual eles podem:

1. Cadastrar dados pessoais ex: (CPF, E-MAIL e Telefone), escolaridade, renda, etnia e raça;
2. Realizar upload de arquivo de comprovação de pertencimento a instituição;
3. Realizar upload de arquivo de declaração de renda;
4. Ambos uploads só devem ser permitidos com as extensões (docx, doc e pdf).
5. O candidato recebe um e-mail com um número único identificador, que será utilizado em qualquer lugar que seja solicitado como cotista e esse número é válido por 1 ano.




