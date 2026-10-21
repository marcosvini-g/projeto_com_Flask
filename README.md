### Documentação


# 1 Criar uma pasta chamada: projeto_com_flask

# 2 Realizar a instalação do UV

- Abrir o site "https://docs.astral.sh/uv/getting-started/installation/#installation-methods" e clicar no botão "installation"
- Depois de clicar, clicar no botão "Windows" para copiar o comando que será usado no terminal, sendo : powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

# 3 Pós instalação

- Utilizar os comandos: uv init(para iniciar o uv) e uv venv; para inicializar o ambiente virtual
- Use o comando python -V para ver sua versão atual
- Se a versão for inferior a 3.15.0, usar o comando: uv install python 3.15.0
- Para sincronizar as versões, deve utilizar o comando: uv sync. após isso feche o terminal e o seu VScode para funcionar
- Utilizar o comando: uv add Flask para adicionar o framework e conseguir rodar o projeto

# 4 UV no python

- Usamos @app.route("/") para definir a rota que modificamos apartir desse trecho
- A partir desse comando, podemos selecionar dentro do parenteses o que queremos que aconteça apartir de tal escritura, como ("/pessoa")
- Depois da rota definida conseguimos manipular o que acontecerá a partir do que digitaremos, como return "Olá mundo!"
- com o @app.route("...") da para criar varias rotas através de continuações apartir da /
