# API REST FULL SPRING BOOT COM MONGO DB

## Instalação do MongoDB

### Checklist Windows:

- https://www.mongodb.com -> Download -> Community Server

  - Baixar e realizar a instalação com opção "Complete"

- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/ -> Set up the MongoDB environment

- Criar pasta \data\db

- Acrescentar em PATH: C:\Program Files\MongoDB\Server\7.x\bin (adapte para sua versão)

- Testar no terminal: mongod

### Checklist Mac:

- https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/

- Instalar brew:

  - https://brew.sh -> executar o comando apresentado na primeira página

- Instalar o MongoDB:

  - **brew install mongodb**

- Criar pasta /data/db:

  - **sudo mkdir -p /data/db**

- Liberar acesso na pasta criada

  - **whoami** (para ver seu nome de usuário, exemplo: maycon)
  - **sudo chown** -Rv maycon /data/db

- Testar no terminal:
  - **mongod**
