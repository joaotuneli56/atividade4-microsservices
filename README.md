# Atividade Fornecedores 

### **Descrição do Exercício:**

1 - Criar uma service ChatService e transferir toda lógica da conexão ao hub para este serviço; 

2 - Criar um estilo bem bonito para o nosso chat.


# Como rodar o projeto

- [ ] 1º Clonar o repositorio Github.

```
git clone https://github.com/joaotuneli56/atividade4-microsservices.git
```

- [ ] 2° Entrar no repositorio do webchat

```git
cd webchat
```

- [ ] 3º Rode o comando a baixo para instalar o pacote do signalR

```
dotnet add package Microsoft.AspNetCore.SignalR
```

- [ ] 4º Rode o projeto webchat no backend

- [ ] 5º Entre na pasta `app-angular´

```
cd app-angular
```

- [ ] 6º Instale as dependencias do angular

```
npm install -g @angular/cli
```

- [ ] 6º Faça o rebuild da aplicação angular

```
npm install
```

**CASO O PROJETO ESTEJA COM ERRO**, rode o comando abaixo:

```
Set-ExecutionPolicy RemoteSigned
```

- [ ] 7º Rode o projeto para teste

```
ng serve
```