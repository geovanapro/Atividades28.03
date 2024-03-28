# Atividades28.03

# Códigos SQL
Para adicionar coluna 'estado' ou 'cidade' à tabela 'alunos'
ex:

ALTER TABLE alunos
ADD estado VARCHAR(2);

# ESTADO/CIDADE

Para atualizar/adicionar informações em 'estado' e 'cidade':
Ex:

UPDATE alunos
  SET estado = 'SP', cidade = 'Campinas'
WHERE id IN (9, 28);

# Para listar em ordem

SELECT * FROM alunos ORDER BY nome;
SELECT * FROM alunos ORDER BY id;
SELECT * FROM alunos ORDER BY estado;
SELECT * FROM alunos ORDER BY idade;

# ATIVIDADE DA MÚSICA 

Para criar a tabela:

CREATE TABLE Músicas (
ID INT (11),
Musica VARCHAR (255),
Artista VARCHAR (255),
Idioma VARCHAR (255),
Duração INT (11);
);

Para Adicionar as músicas:

INSERT INTO Músicas (ID, Musica, Artista, Idioma, Duração)
VALUES
(1, "Já estive em outros lugares", 'Alessandro Vilas Boas','PT-BR', 10),
