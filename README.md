# App

Gym pass style app

## RFs (Requisitos funcionais)

- [ ] Deve ser possivel se cadastrar
- [ ] Deve ser possivel se autenticar
- [ ] Deve ser possivel obter o perfil de um usuário logado
- [ ] Deve ser possivel obter o numero de checkins realizado pelo usuaroi logado
- [ ] Deve ser possivel o usuário obter seu histórico de checkins
- [ ] Deve ser possivel o usuário buscar academias proximas
- [ ] Deve ser possivel o usuário buscar academias pelo nome
- [ ] deve ser possível o usuário realizar checkin em uma academia
- [ ] Deev ser possivel validar o checkin de um usuário
- [ ] Deve ser possivel cadastrar uma academia

## RNs (Regras de Negócio)

- [ ] O usuário não deve poder se cadastrar com o email duplicado
- [ ] O usuário não pode fazer 2 checkins no mesmo dia
- [ ] O usuário não pode fazer checkin se não estiver perto (100m) da academia
- [ ] O check-in só pode ser validado até 20 minutos após criado
- [ ] O check-in so pode ser validado por administradores
- [ ] A academia só pode ser cadastrada por administradores

## RNFs (Requisitos não funcionais)

- [ ] A senha do usuário precisa estar criptografada
- [ ] Os dados da aplicação precisam estar persistidos em um banco postgrees sql
- [ ] Todas listas de dados precisam estar paginadas com 20 intens por pagina
- [ ] O usuário precisa ser identificado por um JWT

instalacao e config fo prisma
inicialização do prisma
inicialização da imagem do postgres no docker com config de database
npx prisma migrate dev
