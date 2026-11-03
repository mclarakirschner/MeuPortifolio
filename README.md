# Maria Clara | Portfólio

Portfólio pessoal desenvolvido com **Python, Flask, HTML e CSS**.

## Executar no computador

1. Instale Python 3.
2. No terminal, instale as dependências:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Inicie o projeto:

   ```bash
   python app.py
   ```

4. Acesse `http://127.0.0.1:5000/`.

## Publicar na internet com Render

1. Crie um repositório **público** no GitHub (por exemplo, `portfolio-maria-clara`).
2. Envie todos os arquivos desta pasta para a branch `main`.
3. Entre em https://render.com/ e crie uma conta.
4. Escolha **New +** → **Web Service** e conecte sua conta do GitHub.
5. Selecione o repositório do portfólio.
6. Configure:
   - **Runtime:** Python
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `gunicorn app:app`
7. Clique em **Deploy Web Service**.
8. Quando o deploy terminar, o Render fornecerá um endereço público `onrender.com` para compartilhar.

O arquivo `render.yaml` já contém as configurações básicas para o serviço. Se o Render reconhecer o Blueprint, poderá preencher esses comandos automaticamente.

## Tecnologias

- Python e Flask
- HTML5 e CSS3
- Logos de tecnologias carregados do Devicon por CDN

## Estrutura

```text
portfolio-maria-clara/
├── app.py
├── requirements.txt
├── render.yaml
├── templates/
│   └── index.html
└── static/
    └── css/
        └── style.css
```

**Observação:** o site usa logos hospedados externamente pelo Devicon; por isso, é necessário estar conectado à internet para carregá-los.
