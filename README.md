# CIDADE E ALUNO BD
### INNER JOIN juntando as duas tabelas e usando alias
```bash
  SELECT a.id AS RA,
  a.nome AS Nome,
  a.data_nasc AS `Data de Nascimento`,
  c.nome AS Cidade,
  c.populacao AS `População`
  FROM alunos a
  INNER JOIN cidades c ON (c.id = a.cidade_id)
```
