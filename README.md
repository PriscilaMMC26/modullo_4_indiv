A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.

Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo:

⇨ Existem outras entidades além dessas três?
Sim. Instituição, monitores e facilitadores.

⇨ Quais são os principais campos e tipos?
Nome, cpf, email, endereço e telefone.

⇨ Como essas entidades estão relacionadas?
Uma instituição para muitos cursos (1:n),
Um curso para muitas turmas (1:n),
Um aluno para muitos cursos (1:n),
Um facilitador para muitas turmas (1:n),
Um monitor para muitas turmas (1:n).
![diagrama](https://github.com/PriscilaMMC26/modullo_4_indiv/blob/main/modulo_4.png)
