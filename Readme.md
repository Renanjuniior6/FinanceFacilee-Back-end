<h1 align="center">📊 API FinanceFacilee</h1>

## 👇 É recomendável ter em sua máquina para rodar
- [Node](https://nodejs.org/pt) 21.0^
- [Docker](https://www.docker.com/) Desktop ou Docker CLI 
- [WSL2](https://learn.microsoft.com/pt-br/windows/wsl/install) (se seu sistema for Windows)

## 🌐 Rodando a API localmente

```bash
# Faça o git clone do projeto
$ git clone [URL]

# Instale as depedências
$ npm install

# Para executar digite
$ npm run dev

# Ao rodar usando Docker certificar de que o banco de dados está de pé. Caso contrário irá apresentar erro ao rodar a aplicação;
```

## 🌐 Rodando o container do MongoDB no Docker

```bash
# Com o docker desktop instalado na sua máquina, execute este comando para subir o banco
$ docker compose up

# Caso queira derrubar o container execute
$ docker compose down

# Caso queira parar o container execute
$ docker compose stop
```
