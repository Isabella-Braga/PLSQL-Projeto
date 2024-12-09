# Projeto PL/SQL: Gestão de Alunos, Disciplinas e Professores

Este repositório contém um script PL/SQL para a criação de tabelas, sequências e pacotes relacionados à gestão de Alunos, Disciplinas e Professores. O script foi desenvolvido para atender requisitos acadêmicos, incluindo operações de manipulação de dados e consulta usando procedures, functions e cursores.

## Como usar

1. Baixe o arquivo `script.sql`.
2. Abra o Oracle SQL Developer (ou ferramenta equivalente).
3. Conecte-se ao banco de dados Oracle.
4. Execute o script para criar as tabelas, sequências e pacotes.
5. Use os pacotes para realizar as operações descritas abaixo.

## Funcionalidades

### Pacote `PKG_ALUNO`
- **Excluir Aluno**: Remove um aluno e suas matrículas associadas.
- **Listar Alunos Maiores de 18 Anos**: Retorna um cursor com os alunos maiores de idade.
- **Listar Alunos por Curso**: Filtra alunos por um curso específico.

### Pacote `PKG_DISCIPLINA`
- **Cadastrar Disciplina**: Insere uma nova disciplina no banco de dados.
- **Total de Alunos por Disciplina**: Retorna um cursor com o número de alunos matriculados por disciplina.
- **Média de Idade por Disciplina**: Calcula a média de idade dos alunos de uma disciplina específica.
- **Listar Alunos da Disciplina**: Exibe os nomes dos alunos matriculados em uma disciplina.

### Pacote `PKG_PROFESSOR`
- **Total de Turmas por Professor**: Retorna o número de turmas de um professor.
- **Professor de uma Disciplina**: Identifica o professor responsável por uma disciplina específica.

## Estrutura de Tabelas

- **`ALUNO`**: Contém informações dos alunos.
- **`DISCIPLINA`**: Contém informações das disciplinas.
- **`PROFESSOR`**: Contém informações dos professores.
- **`MATRICULA`**: Relaciona alunos e disciplinas.
- **`TURMA`**: Relaciona disciplinas e professores.

## Requisitos

- Oracle Database.
- Ferramenta de execução de scripts SQL (ex.: SQL Developer).

## Autor
Isabella Braga
