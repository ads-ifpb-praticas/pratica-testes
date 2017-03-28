# Atividade Prática - Testes de software

O objetivo desta atividade é praticar os conceitos de testes de unidade, testes de integração e testes de sistema. Deverá ser construído um sistema simples para alugar e devolver filmes.

Regras do sistema:

• Os nomes dos títulos não podem possuir caracteres especiais, exceto #,!,? e devem conter até 50 caracteres

• Os títulos devem obrigatoriamente ter um gênero

• A duração dos filmes nao podem ser 0 minutos

• Não deve ser possível editar filmes que estão com estado emprestado

• O empréstimo de filmes não pode ocorrer em datas retroativas

• A devolução não pode ser em data anterior a locação

Crie testes que consigam cobrir todas as regras do sistema. Utilize o plugin do Maven **cobertura** para ter uma visão melhor do seu trabalho. A quantidade de testes fica a cargo do aluno, contanto que contemple todos os tipos de testes vistos em sala de aula.

Utilize uma base de dados embarcada, como o H2 (https://github.com/ads-ifpb-praticas/exemplo-h2), isso vai facilitar a avaliação :)
