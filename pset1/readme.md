## 2.0 Arquivo SQL Power Architect e PDF:
### 2.1 Arquivo SQL Power Architect:
Como principal arquivo aqui guardado, você receberá informações da replicação exata do Projeto de Banco de Dados 
Lojas UVV, o mesmo que foi utilizado em minha primeira avaliação bimestral. O arquivo poderá ser aberto em um 
programa como SQL Power Architect, já que foi neste mesmo que eu o criei, abrindo você poderá visualizar 
comentários sobre cada coluna e tabela criada.
### 2.2 Arquivo em PDF:
Também foi realizado a exportação do arquivo Power Architect como PDF para a melhor visualização de usuário que
não possuem um programa de leitura de arquivo .architect. Logo em seguida diversas questões discursivas foram
realizadas sobre o tal projeto lógico, que graças a consulta de diversos sites e discussões  entre alunos, alunos
estes que serão citados mais afrente, as questões foram cumpridas.
## 3.0 Script SQL implementado:
### 3.1 Implementação no PostgreSQL:
Mesmo sendo um SGBD mais difícil e avançado, principalmente pelo fato de possuir uma alta gama de recursos que 
permitem consultas complexas, o Banco de Dados está inicialmente implementado aqui, graças a ferramenta de 
exportação do Power Architect que facilitou o trabalho intensamente. Abrindo o arquivo com qualquer leitor 
.sql, aqui em minha maquina foi utilizado o Visual Studio Code, você inicialmente perceberá que o arquivo 
está totalmente comentado, com diversas Contraints de checagem principalmente de números naturais. A execução
é realizada nos seguintes passos:
- Os bancos de dados com nome UVV são derrubados.
- Os usuários com nome de novelli são derrubados.
- É criado um usuário novelli com a permissão de manipular dados.
- A senha para o usuário novelli foi estabelecida como 123
- É criado o banco de dados UVV conforme as especificações do professor.
- Ocorre a conexão com o banco de dados UVV com o usuário e senha estabelecidos.
- É criado um Esquema, conforme as instruições do professor.
- É configurado o Esquema, conforme as instruções do professor.
- Assim, o banco de dados é criado com as devidas constraints de checagem e comentários.
- Um comentário sobre o banco de dados é feito.
## 4.0 Discursivas e tentativa de implementação:
Por fim, foram realizadas o restante das questões discursivas, sendo fruto de diversos debates entre os
próprios alunos, pesquisas a diferentes sites, e consulta a alunos de períodos superiores, novamente, todos
os créditos aos alunos que me ajudaram serão citados no final desta leitura.
### Não foi feito a implementação no MySQL e MariaDB ### 
Devido a complexidade da troca de conexão, ainda assim, este repositório receberá uma atualização com essa tal 
implementação, mesmo que não deva valer nota para mim, porém, foram realizadas tentativas suficientes para o 
usuário ter uma opnião própria sobre estas ferramentas, tal opnião e comparação dita nas questões discursivas.
## 5.0 Créditos.
- Arthur Morgado. - Após uma tarde na UVV, descobrimos o botão de trocar conexão, além de me ajudar nas discursivas.
- Arthur de Salles. - Também foi um dos alunos que participou desta tarde, esses dois charás são incríveis.
- Samuel Barbosa. - Me ajudou também nas questões discursivas, e também ficou a tarde conosco.
- Roberto Bastos. - O aluno de período que me ajudou para descobrir o código de troca de conexão, além de se prontificar 
a sempre me apoiar nas questões difíceis.
