<h1>Fandankerb</h>
<h2>Trabalho de Banco de Dados</h2>

<hr>

<h3>Requisitos</h3>
<p>
  A Fandankerb está no negócio de aluguel de instrumentos para bandas.
</p>
<p>
  A Fandankerb mantém registros de instrumentos, bandas, reparos técnicos e shows;
</p>
<p>
  Para cada instrumento, a Fandankerb mantém um registro do número serial (único) assim como o modelo e a marca, o ano em que um instrumento foi fabricado e a idade do instrumento medida em anos;
</p>
<p>
  Os clientes da Fandankerb são as bandas. Para cada banda, registra-se o nome único e o identificador único da banda, assim como o endereço de pessoa de contato e múltiplos números de telefone;
</p>
<p>
  Os técnicos de reparo cuidam dos instrumentos, para cada técnico a Fandankerb registra o CPF, o nome, o endereço e múltiplos números de telefone;
</p>
<p>
  A Fandankerb registra informações sobre os shows em que os clientes se apresentaram. Para cada show registra-se um identificador único do show composto pelo nome do local e pela data. Para cada show também se registra o tipo de show e o nome, sendo que um show pode ou não ter um nome;
</p>
<p>
  Uma banda não precisa alugar nenhum instrumento e pode alugar até 30. Cada instrumento pode ser alugado por uma banda ou por nenhuma;
</p>
<p>
  Um técnico de reparo conserta um ou muitos instrumentos. Cada instrumento é consertado por apenas um técnico;
</p>
<p>
  Uma banda pode apresentar-se em muitos shows ou em nenhum. Cada show deve ter ao menos uma banda se apresentando e pode ter muitas bandas. Para cada instância de banda performando em um show se registra a duração em minutos da apresentação daquela banda;
</p>
<p>
  Para cada banda, a Fandankerb registra a quantidade de shows em que ela se apresentou;
</p>
<p>
  Para cada show, a Fandankerb registra a quantidade de bandas que se apresentaram naquele show.
</p>

<hr>

<h3>Exigências</h3>

<ol>
  <li><s>Diagrama ER da Fandankerb;</s></li>

  <li><s>Diagrama do esquema relacional da Fandankerb;</s></li>

  <li><s>No mínimo 3 registros de exemplo por tabela;</s></li>

  <li><s>Observar a 3FN;</s></li>

  <li>Instruções SQL DDL para a criação do banco de dados;</li>

  <li>Instruções SQL DML para a inserção dos registros de exemplo em todas as tabelas;</li>

  <li>Implantação do banco de dados da Fandankerb no banco de dados do laboratório;</li>

  <li>Criação do diagrama do esquema relacional dentro do banco de dados do laboratório;</li>

  <li>Elaboração de uma instrução SQL que liste a quantidade de shows em que se apresentou uma determinada banda.</li>
</ol>
