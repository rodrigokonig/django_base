# django_base
Projeto Django Standard para Uso em Novos Apps

OBS: O comando py é utilizado para executar o Python, caso não tenha instalado o Python, instale-o primeiro. 
Esse exemplo foi construido no Windows. Para Linux e IOs, os comandos podem variar.

=== ESTRUTURA ===
- **app**: Pasta do projeto
- **app/settings.py**: Configurações do projeto
- **app/urls.py**: Rotas do projeto
- **app/templates**: Templates do projeto
- **app/templates/layouts**: Layout dos Templates do projeto
- **app/templates/includes**: Includes do projeto
- **app/static**: Arquivos estáticos do projeto
- **core**: APP Inicial do projeto
- **core/models.py**: Modelos do App
- **core/views.py**: Views do App
- **core/forms.py**: Formulários do App
- **core/admin.py**: Administração do App
- **core/apps.py**: Configuração do APP
- **core/templates**: Templates do APP (home -> inicialmente)
- **core/static**: Arquivos estáticos do App


=== AMBIENTE VIRTUAL ===

1 - Crie e Ative o Ambiente Virtual:
py -m venv venv
/venv/scripts/activate && cls 

2 - Atualize o pip (Instalador de pacotes do Python)
python.exe -m pip install --upgrade pip

3 - Verifique se o VSCODE (caso esteja utilizando ele) está com Ambiente Virtual configurado para venv
CRTL + Shift
Python Select Interpreter
Escolha o Venv


=== INSTALANDO AS DEPENDÊNCIAS ===

4 - Instale as Dependências:
pip install -r requirements.txt


=== TESTE DE EXECUÇÃO ===

5 - Execute o Projeto:
No terminal entre na pasta do projeto (app) e execute o comando:
python manage.py runserver

=== PAINEL ADMINISTRATIVO ===

6 - Entre na pagina de login:
localhost:8000/admin
username: admin
password: Admin123##

Edite os dados de Nome, Sobrenome, Email e Senha para o novo SuperUser
