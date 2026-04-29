CREATE TABLE alunos (
    id TEXT PRIMARY KEY,
    nome TEXT
);

CREATE TABLE registros (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    aluno_id TEXT,
    horario TEXT,
    status TEXT
);
