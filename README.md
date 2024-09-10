# Planner Application

## Descrição

O **Planner** é uma aplicação desenvolvida com o intuito de organizar viagens e eventos, gerenciando atividades, links úteis, e participantes. A aplicação permite o planejamento de detalhes de uma viagem, incluindo o gerenciamento de atividades relacionadas e a confirmação de participação de usuários.

## Funcionalidades

- **Gerenciamento de Atividades**: Criação e listagem de atividades relacionadas a uma viagem.
- **Gerenciamento de Links**: Adicione links úteis para cada viagem.
- **Confirmação de Participantes**: Permite que participantes confirmem sua presença em uma viagem.
- **Integração com banco de dados**: Persistência de dados relacionados a atividades, links e participantes utilizando um banco de dados relacional.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- **Entities**:
  - `Activity`: Representa uma atividade planejada para a viagem, com data e título.
  - `Link`: Representa links úteis associados a uma viagem.
  - `Participant`: Representa os participantes que podem confirmar presença em uma viagem.
- **Repositories**:
  - `ActivityRepository`: Realiza operações de CRUD relacionadas a atividades.
  - `ParticipantRepository`: Gerencia as interações relacionadas a participantes, como confirmação de presença.
- **Controller**:
  - `ParticipantController`: Controla as rotas relacionadas aos participantes, permitindo a confirmação via API.
  
## Tecnologias Utilizadas

- **Spring Boot**: Framework para construir aplicações Java com configuração mínima.
- **JPA/Hibernate**: Mapeamento objeto-relacional para persistência de dados.
- **Banco de Dados**: MySQL ou outro banco relacional configurado.
- **Lombok**: Simplificação de código com anotações para getters, setters, construtores, etc.
- **Java 17**: Linguagem de programação utilizada.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/planner.git
