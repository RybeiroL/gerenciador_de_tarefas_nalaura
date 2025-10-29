# Gerenciador de Tarefas Nalaura

Este é um aplicativo simples de gerenciamento de tarefas usando **FastAPI**, **SQLite** e **Jinja2**.

## Como rodar localmente

1. Crie um ambiente virtual:
```bash
python -m venv venv
```
2. Ative o ambiente virtual:
```bash
.env\Scripts\activate
```
3. Instale as dependências:
```bash
pip install -r requirements.txt
```
4. Execute o aplicativo:
```bash
uvicorn main:app --reload
```
5. Abra o navegador em `http://127.0.0.1:8000` para ver o gerenciador de tarefas.

## Git e GitHub

1. Inicialize o repositório Git local:
```bash
git init
```
2. Adicione os arquivos e faça o commit inicial:
```bash
git add .
git commit -m "Initial commit"
```
3. Crie o repositório no GitHub e conecte:
```bash
git remote add origin https://github.com/SEU_USUARIO/gerenciador_de_tarefas_nalaura.git
git branch -M main
git push -u origin main
```

## CI/CD com GitHub Actions

O arquivo `.github/workflows/ci.yml` irá rodar automaticamente checks toda vez que houver push ou pull request.
