# Modelagem do Banco de Dados
Repositório para modelagem do banco de dados

<div align="center">
  <img src="avaliacao.L.png"/>
</div>
<h2>Tabela <i>Alunos</i></h2>
A tabela <i>alunos</i> descreve dentro no modelo relacional elaborado, onde e quais atributos iremos manter no banco
sobre nosso sistema do aluno.
Nela possuímos os atributos/colunas:
<ul>
  <li>MAT: chave primária da tabela</li>
  <li>Nome: nome do aluno.</li>
  <li>Endereço: local onde reside o aluno</li>
  <li>Cidade: cidade onde mora</li>
  <li>fk_historico_MAT: chave estrangeira que faz referência a tabela <i>historico</i></li>
</ul>

<h2>Tabela <i>Disciplinas</i></h2>
A tabela <i>disciplina</i> será na nossa base de dados a responsável por manter os dados das disciplinas do sistema.
Nela possuímos os atributos/colunas:
<ul>
  <li>COD_DISC: chave primária da tabela</li>
  <li>Nome_DISC: nome da materia</li>
  <li>Carga_hor: horario das aulas</li>
  <li>fk_historico_MAT:chave estrangeira que faz referência a tabela <i>historico</i></li>
  </ul>

<h2>Tabela <i>Professores</i></h2>
Tabela de <i>professores</i> aqui teremos na nossa base informações sobre os professores.
Nela possuímos os atributos/colunas:
<ul>
  <li>COD_PROF: chave primária da tabela</li>
  <li>Nome: nome do professor</li>
  <li>Endereço:local onde reside o professor </li>
  <li>Cidade: cidade onde mora</li>
  <li>fk_historico_MAT:chave estrangeira que faz referência a tabela <i>historico</></li>
 </ul>
 
<h2>Tabela <i>Turma</i></h2>
Tabela <i>turma</i> com as informações sobre a turma </i></i> <i></i>.
Nela possuímos os atributos/colunas:
<ul>
  <li>COD_DISC: chave primária da tabela <i></i></li>
  <li>COD_TURMA: identificador da turma <i></i> </li>
  <li>COD_PROF: chave estrangeira que faz referencia a tabela professores(cod_prof)<i></i></li>
  <li>ANO: série da turma <i></i></li>
  <li>Horario: horario de entrada e saída <i></i></li>
  <li>fk_historico_MAT: chave estrangeira que faz referência a tabela historico<i></i></li>
</ul>

<h2>Tabela <i>Historico</i></h2>
Tabela <i>historico</i> nesta tabela colocamos todo o historico do aluno.
Nela possuímos os atributos/colunas:
<ul>
  <li>MAT:chave primária da tabela </li>
  <li>COD_DISC:identificador de disciplina <i></i></li>
  <li>COD_TURMA:identificador da turma <i></i> </li>
  <li>COD_PROF:identificador do professor(a) <i></i></li>
  <li>ANO: série do aluno <i></i></li>
  <li>frequencia:frequencia com que o aluno está indo as aulas<i></i></li>
  <li>nota:nota do aluno<i></i></li>
</ul>


