### Sistema de Gerenciamento de Candidatos - CNH Social

Este repositório contém o código-fonte de um sistema desenvolvido para gerenciar candidatos ao projeto CNH Social. O sistema foi construído utilizando Python e o framework Django, com Bootstrap 5 para a interface de usuário. Para o banco de dados de teste, utilizou-se o SQLite.

#### Funcionalidades

- **Cadastro de Candidatos**: Permite a inclusão, edição e exclusão de candidatos no sistema.
- **Listagem e Pesquisa**: Exibe a lista de candidatos cadastrados, com opções de pesquisa e filtros.
- **Gerenciamento de Processos**: Controle de status e fases dos candidatos no projeto CNH Social.
- **Relatórios**: Geração de relatórios detalhados sobre os candidatos e seus processos.
- **Autenticação e Autorização**: Sistema de login e controle de acesso baseado em permissões.

#### Tecnologias Utilizadas

- **Linguagem**: Python
- **Framework Web**: Django
- **Interface de Usuário**: Bootstrap 5
- **Banco de Dados de Teste**: SQLite

#### Requisitos

- Python 3.6 ou superior
- Django 3.2 ou superior
- Bootstrap 5
- SQLite (para ambiente de teste)

#### Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Daniel-da-Silva-Alves/Sistema-de-controle-de-cadastros---CNH-Social.git
   cd Sistema-de-controle-de-cadastros---CNH-Social
   ```

2. **Crie um ambiente virtual**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # No Windows use `venv\Scripts\activate`
   ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute as migrações**:
   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor de desenvolvimento**:
   ```bash
   python manage.py runserver
   ```

6. **Acesse o sistema**:
   Abra o navegador e acesse `http://127.0.0.1:8000/`

#### Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests. Para grandes mudanças, por favor, abra uma issue primeiro para discutir o que você gostaria de mudar.

#### Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
