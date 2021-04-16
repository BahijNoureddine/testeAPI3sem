## API 3º Semestre - Banco de Dados

<p align="center"> <img src="https://user-images.githubusercontent.com/18652465/111547833-88631a00-8758-11eb-863c-ccf1e6e93f39.png"> </p>

<h1></h1> 

### Objetivo:
 O Trace Finder tem como objetivo ser uma aplicação que permite manter, customizar e versionar partes de documentos que são armazenados em arquivos PDF, a partir disso, utilizando regras específicas, é possível gerar documentos finais que integrem as partes selecionadas.

<h1> </h1>

### Sprint 2
Após a entrega da Sprint passada, focamos mais na comunicação com o cliente para um melhor entendimento do problema, através disso foi necessário uma reformulação da idéia inicial.<br>
  Conforme descrito pelo cliente há á necessidade de poder gerenciar o codelist(tabela que traz informações e regras sobre a estrutura do manual), podendo inserir novas linhas, alterar e exclui-las, possibilitando assim mais controle ao usuario.<br>
  Foi adicionado o CRUD de documentos que possibilita ao usuario inserir, pesquisar, editar e deletar manuais. <br>
  Inserimos a opção de controle de traços onde o usuario poderá inserir tantos traços quanto forem necessários e a possibilidade de vincula-los aos documentos.<br>
  A vinculação de traços tambem se aplica aos blocos dos manuais, porem, segue outra regra, somente serão atribuidos aos blocos traços que pertencem ao documento, sendo esta atribuição realizada no codelist.<br>
  Atendendo as necessidades da reformulação do projeto, nosso banco de dados foi atualizado seguindo o seguinte modelo:
  
  <img src=https://user-images.githubusercontent.com/18652465/115090209-a86a3280-9eea-11eb-9f20-b9238a84cced.jpeg border=1 />
 
- [👨‍💻 User Story Cards](https://github.com/MaXximiles/API-3SEM/tree/main/User%20Story%20Cards)
- [📏 Wireframes](https://github.com/MaXximiles/API-3SEM/tree/main/Wireframes)
- [📃 Documentação](https://github.com/MaXximiles/API-3SEM/tree/main/Documenta%C3%A7%C3%A3o)







<h1> </h1>

