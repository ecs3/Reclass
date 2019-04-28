##PROPOSTA
##RECLASS
28/04/2019

##VISÃO GERAL

1. Descrição e histórico do projeto
O Reclass é um aplicativo para ajudar aos alunos que tem dificuldade em absorve os assuntos dados em aulas
presenciais, dando a eles a oportunidade de revisitar o assunto abordado em sala. O aplicativo tem as funções
de gravar áudio e registrar imagens de forma auto organizada, de tal maneira que, os registros audiovisuais
ficam disponíveis, armazenados e separados explicitamente por disciplina e data.

2. Usuários da aplicação
Alunos de cursos presenciais.

3. Aplicativos similares
Os aplicativos que implementam a função de registro áudio visual não dão suporte a organização por assunto,
ficando a organização única e exclusivamente pelo nome e data dos registros. O Reclass dará suporte a
organização dos registros não apenas pela data, mas também pela disciplina daqueles registros.

4. Estrutura da aplicação
	i) Tela de boas vindas do aplicativo.
	ii) Tela de menu com as disciplinas já registradas, com a opção de remover ou adicionar novas
	matérias. Assim como acesso as configurações para se escolher qualidade e formato do áudio a
	ser salvo.
	iii) Ao clicar numa disciplina existente, ira para a lista de aulas gravas com a opção de voltar ao menu
	de disciplinas, remover aulas ou gravar novas aulas.
	iv) Ao optar por uma nova gravação, teremos uma tela de gravação com opções de pausar, resumir e
	parar a gravação e a opção de abrir a câmera para capturar imagens.
	v) Ao se apertar stop será pedido o assunto visto naquela aula, esse nome se somará a data e ao
	nome da disciplina. Aqui não haverá a opção de descartar o áudio, apenas de salvar, o descarte
	pode ser feito posteriormente na lista de áudios. Isso, para que o usuário não delete uma aula
	importante por acidente.
	vi) Em seguida o novo item e mostrado na lista de registros daquela disciplina.

5. Fluxo de Navegação
O fluxo de navegação do aplicativo pode ser experimentado através do protótipo do link abaixo:
https://balsamiq.cloud/sgs1ce/phbtavf/r2278?f=N4IgUiBcAMA0IDkpxAYWfAMhkAhHAsjgFo4DSUA2gLoC%2BQ
A%3D

6. Plano de implementação
Inicialmente, confecção do design das telas (Activities), posteriormente conexão entre as telas (Intents), em
seguida, será implementada a captura dos dados audiovisuais (Services, Permissions) e por fim a camada de
persistência para armazenamento do conteúdo (Permissions, Environment)