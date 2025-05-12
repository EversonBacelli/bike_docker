
# 🚴‍♂️ Projeto Bike Docker

Este projeto foi desenvolvido como parte do curso DockerPro, realizado entre fevereiro e maio de 2025, com o objetivo de aplicar e consolidar conhecimentos em Docker e Docker Compose.

---

## 🚀 Tecnologias Utilizadas

O projeto integra diversas tecnologias para simular um ambiente de desenvolvimento completo.

| Tecnologia       | Logo                                                                 | Descrição                                                                 |
|------------------|----------------------------------------------------------------------|---------------------------------------------------------------------------|
| **Docker**       | <img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" height="40"/> | Plataforma para desenvolvimento, envio e execução de aplicações em containers. |
| **Docker Compose** | <img src="https://raw.githubusercontent.com/docker/compose/master/logo.png" height="40"/> | Ferramenta para definir e gerenciar multi-containers Docker.             |
| **Node.js**      | <img src="https://nodejs.org/static/images/logo.svg" height="40"/>   | Ambiente de execução JavaScript assíncrono e orientado a eventos.        |
| **MySQL**        | <img src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" height="40"/> | Sistema de gerenciamento de banco de dados relacional.                  |

---

## 📂 Estrutura do Projeto

O projeto está organizado em três diretórios principais:

- `bd_bike_docker`: Contém os scripts e configurações relacionados ao banco de dados MySQL.
- `mysql_docker`: Configurações específicas para o container do MySQL.
- `server_bike_docker`: Código-fonte do servidor Node.js que interage com o banco de dados.

Além disso, há um arquivo `docker-compose.yaml` na raiz do projeto que orquestra os containers.

---

## 🛠️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/EversonBacelli/bike_docker.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd bike_docker
   ```

3. Inicie os containers com Docker Compose:
   ```bash
   docker-compose up --build
   ```

4. A aplicação estará disponível em `http://localhost:5000` (ou na porta configurada).

---

## 📚 Pré-requisitos

- [Docker](https://www.docker.com/) instalado na máquina.
- [Docker Compose](https://docs.docker.com/compose/) instalado.
- [Node.js](https://nodejs.org/) para desenvolvimento local (opcional).

---

## 👨‍🏫 Autor

Este material foi desenvolvido por [Everson Bacelli](https://github.com/EversonBacelli), professor titular na ETEC de Cidade Tiradentes, nos cursos técnicos de Desenvolvimento de Sistemas e Informática para Internet.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

---
