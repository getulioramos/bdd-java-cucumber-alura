
# BDD Java Cucumber - Leilao - ALURA

# Índice 

* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Conclusão](#conclusão)

# 💻 Descrição do Projeto 💻

Neste projeto vamos ententeder que é o BDD? Como  Behavior Driven Development se encaixa no universo de teste e no processo ágil? Ou quais são as vantagens de usar e principalmente como usar?

Cucumber ou Gherkin já conhece? Se sim ou não, não importa, neste projeto irá aprender sobre essa ferramenta e como o BDD em geral se encaixa no mundo de ágil.

Então além de entender e formalizar todo esse processo, nós vamos usar o Cucumber, e vamos usar o Selenium "por baixo dos panos" para criar especificações executáveis e colocar as especificações no nosso código para testar e transformar isso em código e testar através de vários passos, em uma aplicação real.

O Bdd neste projeto serve para unificar as infomrçãoes antes de transformarmos  em código para que não haja "telefone sem fio" e as informações seja perdidas.Aqui entram esses famosos Given-When-Then, que todo mundo já ouviu falar.
Então  agora tendo esse conhecimento comum, e tendo essa formalização, esses critérios de aceitação é hora de realmente transformar isso em código, automatizar. E aí sim entra o Cucumber. Entra agora o desenvolvedor usando o TDD (Test-driven development) para transformar isso num design guiado pelos testes.

E entra o Gherkin, que sabe interpretar essa linguagem natural. Ou seja, essa é a fase de realmente implementar as coisas e fazer funcionar baseado naqueles critérios de aceitação.



# Status do Projeto
Finalizado


# PessoasContribuidoras
 Realizei este projeto auxiliado pelas aulas e professores da Alura.
 
 # Tecnologias Utilizadas
- Java
- Selenium
- Cucumber
- JUnit
 
# Conclusão

- O que é BDD (o Behaviour Driven Development)
  - BDD tenta melhorar a comunicação e colaboração
  - BDD tenta aproximar o negócio e criar um entendimento melhor como a aplicação deveria funcionar isso nos vários tipos de testes:
    - testes de unidade
    - testes de integração
    - testes ponta a ponta (end-to-end)
    
 Para melhorar a comunicação nos testes e o entendimento das funcionalidades. O QA trabalhando junto com os desenvolvedores e com os caras do negócio, escrevem isso num documento de texto, seguindo um pequeno padrão de cenários

ou seja, você coloca isso dentro de um “.feature” seguindo a estrutura que o Gherkin exige, seguindo essas palavras chaves, mas que é bem perto do que usamos.

 Feito isso, você já consegue chamar isso com o Cucumber para escrever  Steps.  Então aquela ideia do TDD de test first, primeiro fazer o teste, aqui é a raiz, é até mais forte ainda, porque faz parte do mundo de negócio definir isso e o desenvolvedor depois só “segue”, esses critérios de aceitação.

Vimos todos os detalhes de implementação no código, como escrever, como conectar as coisas usando os exemplos, os Data Tables, como escrever esses métodos, como usar tags e contextos também, no final.

Aprendemos como: 
- Integrar a biblioteca Cucumber na aplicação
- Cucumber pode ser inicializado a partir do junit4 (@RunWith)

- Dentro do .feature escrevemos a funcionalidade e os critérios de aceitação
- Um critério de aceitação segue a estrutura de um teste (passos ou steps)
  - os passos são Given-When-Then ou Dado-Quando-Entao.

