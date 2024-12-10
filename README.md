# Projeto Seabrix Django

Este projeto é uma cópia funcional da Netflix desenvolvida para fins acadêmicos. Ele foi criado utilizando Django e integra várias tecnologias modernas, destacando-se pela implementação de Class-Based Views, estilização avançada e autenticação de usuários.

## Descrição

O objetivo principal foi replicar aspectos fundamentais de plataformas de streaming como a Netflix. O projeto inclui:

* Gerenciamento de usuários: Cadastro e autenticação.
* Estilização CSS: Uso combinado de Bootstrap e Tailwind CSS.
* Gerenciamento de conteúdo: CRUD de filmes com imagens e descrições. (É possível criar novos filmes e séries a partir do admin do Django)
* Banco de dados: Integração com PostgreSQL.

## Recursos Principais

* **Class-Based Views:** Simplificação da lógica de controle e melhor organização.
* **Autenticação de Usuário:** Sistema de login e logout com segurança.
* **Banco de Dados Relacional:** Estruturação eficiente para manipulação de dados de filmes.
* **Estilização Responsiva:** Interfaces otimizadas para diferentes dispositivos.

## Estrutura do Projeto

ProjetoSeabrixDJango/ <br>
│
├── filme/               # App principal do projeto. 
├── media/               # Armazenamento de imagens (thumbnails dos filmes).
├── static/              # Arquivos CSS, JavaScript e imagens.
├── templates/           # Templates HTML reutilizáveis.
├── seabrix/             # Configurações principais do projeto Django.
├── requirements.txt     # Dependências do projeto.
└── Procfile             # Configurações para deploy no Heroku.

## Pré-requisitos

* Python 3.8+
* Django 4.x
* PostgreSQL
* Ambiente virtual configurado.

## Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/Diogo-seabra/ProjetoSeabrixDJango.git
   cd ProjetoSeabrixDJango
   
2. Crie e ative um ambiente virtual:
   ````bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   
3. Instale as dependências:
   ````bash
   pip install -r requirements.txt

4. Configure o banco de dados no arquivo settings.py.

5. Execute as migrações:
   ````bash
   python manage.py migrate

6. Inicie o servidor:
   ````bash
   python manage.py runserver

## Deploy

Este projeto está preparado para deploy no Railway.
Certifique-se de incluir variáveis de ambiente no Railway para configurar o banco de dados e outras dependências.

## Contribuições

Contribuições são bem-vindas! Por favor, envie suas sugestões ou pull requests.

## Autor

Desenvolvido por Diogo Seabra.

Sinta-se à vontade para usar este projeto como referência ou ponto de partida para outros trabalhos!



   
