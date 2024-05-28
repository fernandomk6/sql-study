# Aula

- [Qual a diferença entre INNER e LEFT JOIN? | CreateSe](https://www.youtube.com/watch?v=iaem9hrPNeo)
    - Inner join vai trazer os resultados que existem nas duas tabelas 
    - O left join traz todas as linhas da tabela a esquerda do comando left join que tenha ou não um registro correspondente na outra tabela 
    - Por exemplo: `SELECT * FROM tabela_esquerda LEFT JOIN outra_tabela`
- [Bancos Relacionais! Conheça os JOINs do SQL... INNER, OUTER, FULL, SEMI e ANTI JOIN!](https://www.youtube.com/watch?v=165r4qUvp8Q&t=778s)
    - Inner join vai trazer apenas os dados que se referenciam dentro das duas tabelas 
    - Outer join traz todos os dados que nao se relacionam entre si
    - Left join ou left outer join (sinonimos), traz os dados que se relacionam entre si, e todos os dados que nao se relacionam entre si da tabela à esquerda do comando left join 
- [Banco de Dados - Como fazer Inner Join, Left Join e Right Join](https://www.youtube.com/watch?v=haqW0eg-0tc)
- [SQL: Aula 31 - Como usar o LEFT JOIN?](https://www.youtube.com/watch?v=JH8zpa2Psz8)
- [LEFT JOIN na prática | CreateSe](https://www.youtube.com/watch?v=dVHltNPwr-Q)
- [23 - T-SQL - OUTER JOINS - LEFT e RIGHT - Selecionar dados de várias tabelas - SQL Server](https://www.youtube.com/watch?v=mGbOaA1xWwk)
    - Left join (left outer join): Retorna todas as linhas da tabela à esquerda do comando left join, memso se não houver nenhuma correspondência na tabela à direira 
    - Right join (right outer join): A mesma coisa do left só que troca os lados.
    - Full Join (full outer join): Retorna linhas quando houver uma correspondencia em qualquer uma das tabelas. É uma combinação de left e right join.
    - Left join exclusivo: `SELECT * FROM tabela_esqueda e LEFT JOIN tabela_direita d ON e.d_id = d.id WHERE d.id IS NULL`. Traz todas as linhas da tabela da esquerda que não tenham uma correspondência na tabela da direita. 
