# Origem

O SOLID é um famoso acrônimo, formado pelas letras iniciais de cinco importantes conceitos de design de software. Esses conceitos ajudam o programador a escrever códigos mais limpos, separando responsabilidades, diminuindo acoplamentos, facilitando na refatoração e estimulando o reaproveitamento do código.

# A composição do acrônimo

## SRP: Single Responsibility Principle

O Princípio da Responsabilidade Única afirma que cada módulo de software deve ter um, e apenas um, motivo para mudar.

>"Se uma classe tem mais de uma responsabilidade, as responsabilidades se tornam acopladas. Mudanças em uma responsabilidade podem prejudicar ou inibir a capacidade da classe de cumprir as outras. Esse tipo de acoplamento leva a projetos frágeis que estragam de maneiras inesperadas quando alterados.” (MARTIN 2011)

## OCP: Open Closed Principle

O Princípio Aberto Fechado nos ajuda a ter classes coesas e que evoluam mais fácil. Trata-se de um conceito que objetiva a escrita de classes “abertas para extensão”, mas “fechadas para modificação”. Em outras palavras, deve ser fácil estender o comportamento de uma classe, ao mesmo tempo que ela deve ser fechada para alteração, impedindo sua modificação sempre que a regra de negócio mudar.

>“Para que os sistemas de software sejam fáceis de mudar, eles devem ser projetados de modo a permitirem que o comportamento desses sistemas mude pela adição de um novo código em vez da alteração do código existente..” (MARTIN 2019)

## LSP: Liskov Substitution Principle

O Princípio da Substituição de Liskov originou-se da famosa definição de subtipos de Barbara Liskov. Ao trabalhar com herança é preciso sempre lembrar do contrato estabelecido pela classe pai. Apesar de parecer simples, na prática não é tão fácil e exige um certo talento para organização.

>“Para construir sistemas de software com partes intercambiáveis, essas partes devem aderir a um contrato que permita que essas partes sejam substituídas umas pelas outras” (MARTIN 2019)

## ISP: Interface Segregation Principle

O Princípio da Segregação de Interfaces defende que quando mais coesos e especializados forem os contratos (interfaces) melhor e mais seguras serão as implementações.

Assim sendo, deve-se extinguir a implementação de métodos somente para cumprir a exigência de uma interface inchada (que geralmente estão requerendo mais implementações do que deveriam), ao contrário, deve-se criar interfaces magras, contendo apenas as assinaturas de suas especialidades.

>“O ISP aconselha os projetistas de software a não dependerem de coisas que não usam”. (MARTIN 2019)

## DIP: Dependency Inversion Principle

O Princípio da Inversão de Dependência afirma que se uma classe for depender de outra, esta deve ser mais estável. Ou seja, se a classe A depender da classe B, B deve ser mais estável que A, de forma que as dependências entre as classes sempre sigam em direção à estabilidade, dependendo de módulos mais estáveis que ela própria.

>“O código que implementa a diretiva de alto nível não deve depender do código que implementa detalhes de baixo nível” (MARTIN 2019)

## Referências

[Os Princípios SOLID](https://medium.com/contexto-delimitado/os-princ%C3%ADpios-solid-34b136f507bb) - by Ricardo Dias
