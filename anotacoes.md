--Planejamentos

-Entidades
Usuários 

Usuário x tarefa
Um usuário pode criar várias tarefas

Usuario x Categoria
Um usuário pode ter várias categorias


Tarefas

Tarefa X Usuário
Uma tarefa SEMPRE vai pertencer a um usuário

Tarefa x Categorias
Uma tarefa SEMPRE vai pertencer a uma categoria

Categorias

Categoria X Tarefa
Uma categoria pode TER várias tarefas
Categoria X Usuário
Uma categoria SEMPRE vai pertencer a um usuário


--Detalhamento das Migrations

- Usuário:
-- Padrão do Laravel

- Tarefas:
-Id
-title
-due_date
-description
-category_id
-user_id

- Categoria:
-Id
-name
-color(hexadecimal)
-user_id
