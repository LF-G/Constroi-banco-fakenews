Este pequeno projeto consistiu em construir banco MySQL a partir de tabelas Excel. Fui motivado pelo fato de que a base de dados do projeto "Eleições, fake news
e os tribunais: desinformação onlina nas eleições de 2018", no qual trabalhei quando estava na FGV-SP, foi divulgada para o grande público por meio de tabelas Excel.

A ideia básica foi escrever um script SQL com capacidade de, a partir das tabelas Excel, construir um banco de dados MySQL e copiar todos os dados que estão nessas tabelas
para o banco.

Como as tabelas contêm muitos dados, criei um código em Python que as lê e cria um script SQL capaz de fazer isso.

Este repositório contém o código Python que escreve o script SQL ("escreve_script_SQL.py") e o script escrito após rodar o código ("constroi_banco_decisoes.sql"). O link
para visualizar e fazer download das tabelas Excel cujos dados foram lidos e copiados é este: https://repositorio.fgv.br/items/4c7b6c4e-be63-4f86-b7fb-14eff8cd27b2.
