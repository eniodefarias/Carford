# Carford
sistema para adicionar pessoas e carros com flask


## To-Do List App

### Description

Nork-Town is a weird place. Crows cawk the misty morning while old men squint. 

It’s a small town, so the mayor had a bright idea to limit the number of cars a person may possess. 

One person may have up to 3 vehicles. 

The vehicle, registered to a person, may have one color, ‘yellow’, ‘blue’ or ‘gray’. 

And one of three models, ‘hatch’, ‘sedan’ or ‘convertible’. 

Carford car shop want a system where they can add car owners and cars. 

Car owners may not have cars yet, they need to be marked as a sale opportunity. 

Cars cannot exist in the system without owners.

### Requirements

● Setup the dev environment with docker
○ Using docker-compose with as many volumes as it takes
● Use Python’s Flask framework and any other library
● Use any SQL database
● Secure routes
● Write tests

Time to deliver, 72 hour

------------------------------

## Aplicativo de lista de tarefas

### Descrição

Nork-Town é um lugar estranho. Corvos grasnam na manhã enevoada enquanto os velhos apertam os olhos. 
É uma pequeno cidade, então o prefeito teve a brilhante ideia de limitar o número de carros que uma pessoa pode possuir. 
Um pessoa pode ter até 3 veículos. 
O veículo, registrado para uma pessoa, pode ter uma cor, 'amarelo', 'azul' ou 'cinza'. 
E um dos três modelos, 'hatch', 'sedan' ou 'conversível'.
A loja de carros Carford quer um sistema onde eles possam adicionar proprietários de carros e carros. 
Os proprietários de automóveis que não tiverem carros, precisam ser marcados como uma oportunidade de venda. 
Os carros não podem existir no sistema sem proprietários.

### Requisitos

● Configure o ambiente de desenvolvimento com o docker
○ Usando o docker-compose com quantos volumes forem necessários
● Use a estrutura Flask do Python e qualquer outra biblioteca
● Use qualquer banco de dados SQL
● Rotas seguras
● Escrever testes

Tempo para entregar, 72 horas
------------------------------------

# ⭐️interpretação:

▪️"One person may have up to 3 vehicles" = Pode ter até ter 3 carros
▪️"The vehicle, registered to a person, may have one color, ‘yellow’, ‘blue’ or ‘gray’" = 1 carro pode ter apenas uma das 3 cores.
▪️"And one of three models, ‘hatch’, ‘sedan’ or ‘convertible’" = 1 carro pode ser de um dos 3 modelos.
▪️"Car owners may not have cars yet, they need to be marked as a sale opportunity" = pessoas sem carros devem ser marcadas como oportunidade de venda
▪️"Cars cannot exist in the system without owners" = não pode existir carro sem dono

🟠A regra não indica se a cor e/ou modelo pode ou não repetir para uma pessoa.
🟢A regra só é explicita para 3 carros por pessoa.
🟢Pessoa sem carros devem ser marcadas como oportunidade de venda.
🔵Analise combinatoria = 3x3x3 = 27 combinações por pessoa

