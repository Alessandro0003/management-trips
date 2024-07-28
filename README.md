# Gerenciamento de Viagens 🛩️⚙️

### RFs (Requisitos funcionais)

[x] - Deve ser possível criar uma viagem.

[x] - Deve ser possível convidar participantes para uma viagem.

[x] - Deve ser possível criar um link de certa viagem.

[x] - Deve ser possível Criar uma Atividade.

[x] - Deve ser possível um participante confirma a presença da viagem através de link de confirmação.

[x] - Deve ser possível o criador da viagem confirma a viagem.

[x] - Deve ser possível atualizar uma viagem.

[x] - Deve ser possível listar o link de viagem.

[x] - Deve ser possível listar com detalhe as informações de um participant.

[x] - Deve ser possível listar os Participantes.

[x] - Deve ser possível listar com detalhe as informações de uma viagem.

[x] - Deve ser possível listar as atividades.

### RNFs (Requisitos não-funcionais)

[x] - Não deve ser possível criar uma viagem sem informar. 

    -Destino.
    -Inicio.
    -Fim.
    -Nome do Titular da viagem (owner_name).
    -Email do Titular da viagem (owner_email).
    -Email para confirmação da viagem.

[x] - Não deve ser possível criar uma viagem com uma data ínvalida.
    
    -Exemplo: data que ja se passou.

[x] - Não deve ser possível criar uma convite sem uma viagem criada.

[x] - Não deve ser possível criar uma atividade sem uma viagem criada.

[x] - Não deve ser possível criar uma atividade com uma data fora do dia inicial e o termino da viagem.


### Ferramentas Utilizadas ⚙️

- Node
- Typescript
- Fastify
- Zod
- Prisma
- Dayjs
- Nodemailer

### Usar Aplicação 🚀🔥

- Instalar Dependencias

````bash
    $ npm install
````

- Rodar Aplicação

````bash
    $ npm run dev
````
