# commit-everyday-2022
---
## Janeiro


| Dia      | Commit |
|----------|:--------------:|
|28|Entendendo o Back-end da atividade do estágio.|
|27|Quase finalizando a função e query da atividade do estágio!|
|26|NÃO COMMITEI!!!!!!!!!!! :////|
|25|Função para converter a competência criada no SQL Server<br>*MM/AAAA* para *AAAAMM*<br>Reunião de ensaio com a Data DiscoveryOne|
|24|Adicionei códigos ao repositório do Data Discovery One com as atualizações<br>Wordcloud, contagem e nota média<br>Alias no terminal, com a ajuda desse vídeo:<br>https://www.youtube.com/watch?v=0liXeoADU6A<br>**sudo nano .bash_profile**| 
|23|Git pull no repositório do Data Discovery com o MVP atualizado<br>Foi preciso o *git stash* para 'passar por cima' das modificações locais|
|22|Otimizando o MVP do Data Discovery One<br>Aprendi a criar uma **milestone** aqui no GitHub<br>Aprendi a criar uma **nova linha no conteúdo da tabela**|
|21|Aprendi o comando *git branch -a* para mostrar as branchs do repositório clonado| 
|20       | Inserindo tabela no commit.<br>Aprendi que o Layout pode seguir sem problemas que a formatação continua|

Minha internet está fraca hoje. Aguardando normalizar!


**19**: Criação das Issues no repositório da Atlântico (Data Discovery)

**18**: Consegui criar uma function no MySQL:
```CREATE function fcVerificarSalario(parametro decimal)
RETURNS varchar (20)
deterministic
BEGIN
	declare valorsalario decimal;
	declare situacao varchar(20);
	select salario INTO valorsalario from empregados where codigo = parametro;

	if valorsalario > 1 then
		set situacao = 'Baixo';
	end if;
	return situacao ;	
END $$
delimiter ;
```

Regrinhas:
Função no SQL


Select NOME DA FUNCTION
GO

Para criar uma function:
CREATE FUNCTION (@parametro1 tipo parametro1, @parametro2 tipo parametro2, etc)
RETURNS tipo do retorno (int, varchar, etc)

BEGIN
-- para declarar as variáveis
-- um DECLARE para cada variável

DECLARE @NOME DA VARIAVEL1 tipo da variavel1;
DECLARE @NOME DA VARIAVEL2 tipo da variavel2;

-- depois disso, vem a lógica (ifs, loops, etc)

-- por fim, haverá o retorno
RETURN @variável de retorno

END
GO

Para chamar uma função:
SELECT nomedafuncao FROM tabela


**17**: Função no SQL, como fazer. Ainda estou empacado!


16: Estudos sobre regras de negócio.
Carteira em Análise de Dados
Criação de Currículo para vagas específicas
Otimização do perfil do LinkedIn

15: Post sobre porque criar um blog. Estudos sobre como postar

14: Início de estudos na API; montagem do banco de jogadores do Salinas utilizando o LucidChart.
Criei um código em Python para tirar onda com o SFEP no Instagram (Solta o tantã!) 😂

13: Criação do padrão de análise dados do Salinas. Facilitará para a passagem para Dataframe.

12: Várias movimentações no txt e csv.

11: Tabela do Salinas desenhada e agora passaremos para o LucidChart.
No trabalho, aprendi a criar uma FUNCTION no SQL.
NOTA: FUNCTION retorna algo.
PROCEDURE escreve algo no banco.
Consegui adicionar as funções no JS para coletar os dados dos campos ao clicar o botão. Vamos nessa!

10: Análise do jogo do Salinas realizado. Agora, passaremos os dados para o banco. Pesquisei como plotar um gráfico de setas em uma imagem de campo.
É possível fazer isso com o próprio Python!

09: 
Melhorando os relacionamentos das tabelas do Salinas e pegando referências dos sites de estatísticas esportiva

08: Criei o esquema de banco de dados do Salinas. Estudando tipos de relacionamentos no banco de dados.

07: Consegui adicionar as referências do blog no Readme (assim como criar o próprio readme do blog)

Conheci o [Snipped](https://github.com/jeffersonlicet/snipped/). Excelente para compartilhar códigos direto do VS Code!

06: Planejamento de atividades para os dias. Atualização do Readme do perfil.

05: Google Analytics funcionando no blog!

04: Aprendi o comando gitk. Abre uma nova janela com uma interface para uma melhor visualização.

03: As alterações no site continuam. Hoje também iniciei o projeto Cientista de Dados em 2022. Em breve gravarei o vídeo com o planejamento!

02 de Janeiro: Adiconando o commit pela tarde e com as ideias prontas relacionadas ao Mimo App, Cientista de Dados em 2022 e Study Journal

01 de Janeiro: Inseri alguns arquivos no repositório do site e estou tentando bolar a melhor forma de fazer os commits aqui.

