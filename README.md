
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
  - BDD tenta aproximar o negócio e criar um entendimento melhor como a aplicação deveria funcionar

- Existem vários tipos e níveis de testes, como por exemplo:
  - testes de unidade
  - testes de integração
  - testes ponta a ponta (end-to-end)


- Como integrar a biblioteca Cucumber na aplicação
- Cucumber pode ser inicializado a partir do junit4 (@RunWith)

- Os arquivos .feature são analisados pelo Gherkin e Cucumber
  - Gerkin é uma linguagem para definir os .feature
  - Cucumber gera e roda os passos (steps) associados ao .feature

- Dentro do .feature escrevemos a funcionalidade e os critérios de aceitação
- Um critério de aceitação segue a estrutura de um teste (passos ou steps)
  - os passos são Given-When-Then ou Dado-Quando-Entao
- Cada passo será implementado por um método anotado (step)
- Um arquivo .feature pode ter vários cenários e passos (steps)
- Os métodos associado aos passos são reaproveitados entre cenários
  - podemos passar parâmetros do cenário ao método
- Cucumber possui anotações para inicializar (@Before) e finalizar (@After) o cenários
  - os métodos anotados com @Before e @After são chamados de Hooks
  - cuidado, pois os Hooks não são visíveis no arquivo .feature
