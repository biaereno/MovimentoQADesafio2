<a name="br1"></a>Desafio 2 - Bluesoft

Beatriz Ereno

Melhorias propostas

Melhorias/correções ortográficas

1\. A Label de “Nome completo” está escrita de forma incorreta, como “Nome competo”

○ Foi corrigido para “Nome completo”

2\. O placeholder do CPF não possui a quantidade de caracteres padrão desse tipo de

documento

○ Foi corrigido para “XXX.XXX.XXX-XX”

3\. Placeholder está pedindo apenas o “Nome”. Alterar para pedir o mesmo que a label

○ Foi corrigido para “Nome completo”

4\. Placeholder do campo “Celular” não possui a quantidade de caracteres padrão de

celulares

○ Foi corrigido para “(XX) XXXXX-XXXX”

5\. Placeholder do campo “Data de Nascimento” não possui a quantidade de caracteres

padrão aceito pelo campo (que possui 4 caracteres para o ano)

○ Foi corrigido para “XX/XX/XXXX”

6\. Label “Data Nascimento” falta a palavra “de”

○ Foi corrigido para “Data de Nascimento”

7\. Label do botão “salvr” está escrita errada e sem a primeira letra maiúscula

○ Foi corrigido para “Salvar”

8\. Label do botão “buscar” está em a primeira letra maiúscula

○ Foi corrigido para “Buscar”

9\. Padronizar nome das colunas na tabela

○ Por ser um nome de uma coluna na tabela, vejo que fica melhor sem os dois

pontos “:”

10\. Nome da coluna na tabela com resultados da pesquisa está escrito de forma

incorreta, com “Data deascimento”

○ Foi corrigido para “Data de Nascimento”

11\. Label do botão "Excluirtodos os usuários” está escrita de forma incorreta




<a name="br2"></a>○ Foi corrigido para "Excluir todos os usuários”

12\. Placeholder do campo de busca está escrito “Busca nome”

○ Foi corrigido para “Buscar por nome”

Melhorias/correções de layout

1\. Reduzir e padronizar o espaço entre um campo e outro

○ Foi removido o espaço entre o campo de cpf e o de celular

2\. Te r títulos separando os campos de inclusão e a parte de pesquisa (e ter um

subtítulo para a o resultado da pesquisa)

○ Adicionado um título H2 para “Cadastro de Usuário” e outro para “Consulta

de usuários”,

○ Adicionado um subtítulo H4 para “Usuários cadastrados”, acima da tabela

com as informações dos usuários cadastrados

3\. Trocar as cores do botão vermelho, pois a legibilidade está ruim com o vermelho do

botão e o preto da letra

○ Foi corrigido, alterando o tipo de tag utilizada, trocando a tag ancora <a>

para a tag button <button>

4\. Adicionar o título da página (nome da aba)

○ Foi adicionado o título da página na tag title

5\. Alterar as cores de fundo e das letras do formulário

○ Alteração foi implementada

6\. Centralizar os campos do formulário na página

○ Alteração foi implementada

Melhorias/correções na aplicação

1\. Após inserir um novo usuário, a data de nascimento aparece na tabela com a

palavra “data” após o valor da data de nascimento

○ Retirada a palavra “data” do HTML, não era um problema de salvamento,

mas sim de ter a palavra no arquivo HTML

2\. Aplicação não exibe mensagem de erro após tentativa falha de cadastrar um

usuário, apenas limpa os campos de input, e o usuário novo não é adicionado

○ Não foi corrigido na aplicação

3\. Após clicar em “Excluir todos os usuários”, o ideal é ter uma caixa de confirmação,

para ter certeza de que o usuário quer excluir mesmo todas as informaçõesinseridas

○ Sugestão inserida na aplicação




<a name="br3"></a>4. Aplicação não deixa pesquisar apenas por parte da palavra, precisa ser o nome

completo na pesquisa

○ Não foi corrigido na aplicação

5\. Te r validação de erro após o usuário inserir um dado em formato incorreta em um

campo do cadastro

○ Após o usuário colocar, por exemplo, uma data de nascimento fora do padrão

aceito pela aplicação, o sistema apenas não salva, e não é claro para ousuário que um erro ocorreu

○ Não foi corrigido na aplicação
