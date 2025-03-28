# Barber Shop - Projeto Completo

Este repositório é o ponto central do projeto **Barber Shop**, que consiste em dois subprojetos principais:

- **Backend**: [barber-shop-be](https://github.com/Danielmadr/barber-shop-be) - Implementado em Java com Spring Boot.
- **Frontend**: [barber-shop-fe](https://github.com/Danielmadr/barber-shop-fe) - Desenvolvido em Angular.

## 📂 Estrutura do Repositório

```plaintext
barber-shop-dio/
├── barber-shop-be/   # Submódulo do backend
├── barber-shop-fe/   # Submódulo do frontend
├── .gitmodules       # Configuração dos submódulos
└── README.md         # Documentação principal
```

Cada subdiretório possui seu próprio `README.md` com instruções específicas para configuração e execução.

## 🚀 Como Clonar o Repositório

Este repositório utiliza submódulos Git. Para clonar corretamente, siga os passos abaixo:

1. Clone o repositório principal com o comando:

   ```bash
   git clone --recurse-submodules https://github.com/Danielmadr/barber-shop-dio.git
   ```

   Caso já tenha clonado o repositório sem os submódulos, inicialize-os com:

   ```bash
   git submodule update --init --recursive
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd barber-shop-dio
   ```

## 🛠️ Tecnologias Utilizadas

- **Backend**: Java, Spring Boot, PostgreSQL
- **Frontend**: Angular, Angular Material, Bootstrap
- **Containerização**: Docker e Docker Compose

## 🐳 Executando com Docker Compose

Para executar o projeto completo utilizando Docker Compose:

1. Certifique-se de que o Docker e o Docker Compose estão instalados.
2. No diretório raiz do projeto, execute:

   ```bash
   docker-compose up --build
   ```

3. O backend estará disponível em `http://localhost:8080` e o frontend em `http://localhost:4200`.

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
