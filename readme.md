##PROPOSTA
##RECLASS
28/04/2019

##VIS�O GERAL

1. Descri��o e hist�rico do projeto
O Reclass � um aplicativo para ajudar aos alunos que tem dificuldade em absorve os assuntos dados em aulas
presenciais, dando a eles a oportunidade de revisitar o assunto abordado em sala. O aplicativo tem as fun��es
de gravar �udio e registrar imagens de forma auto organizada, de tal maneira que, os registros audiovisuais
ficam dispon�veis, armazenados e separados explicitamente por disciplina e data.

2. Usu�rios da aplica��o
Alunos de cursos presenciais.

3. Aplicativos similares
Os aplicativos que implementam a fun��o de registro �udio visual n�o d�o suporte a organiza��o por assunto,
ficando a organiza��o �nica e exclusivamente pelo nome e data dos registros. O Reclass dar� suporte a
organiza��o dos registros n�o apenas pela data, mas tamb�m pela disciplina daqueles registros.

4. Estrutura da aplica��o
	i) Tela de boas vindas do aplicativo.
	ii) Tela de menu com as disciplinas j� registradas, com a op��o de remover ou adicionar novas
	mat�rias. Assim como acesso as configura��es para se escolher qualidade e formato do �udio a
	ser salvo.
	iii) Ao clicar numa disciplina existente, ira para a lista de aulas gravas com a op��o de voltar ao menu
	de disciplinas, remover aulas ou gravar novas aulas.
	iv) Ao optar por uma nova grava��o, teremos uma tela de grava��o com op��es de pausar, resumir e
	parar a grava��o e a op��o de abrir a c�mera para capturar imagens.
	v) Ao se apertar stop ser� pedido o assunto visto naquela aula, esse nome se somar� a data e ao
	nome da disciplina. Aqui n�o haver� a op��o de descartar o �udio, apenas de salvar, o descarte
	pode ser feito posteriormente na lista de �udios. Isso, para que o usu�rio n�o delete uma aula
	importante por acidente.
	vi) Em seguida o novo item e mostrado na lista de registros daquela disciplina.

5. Fluxo de Navega��o
O fluxo de navega��o do aplicativo pode ser experimentado atrav�s do prot�tipo do link abaixo:
https://balsamiq.cloud/sgs1ce/phbtavf/r2278?f=N4IgUiBcAMA0IDkpxAYWfAMhkAhHAsjgFo4DSUA2gLoC%2BQ
A%3D

6. Plano de implementa��o
Inicialmente, confec��o do design das telas (Activities), posteriormente conex�o entre as telas (Intents), em
seguida, ser� implementada a captura dos dados audiovisuais (Services, Permissions) e por fim a camada de
persist�ncia para armazenamento do conte�do (Permissions, Environment)