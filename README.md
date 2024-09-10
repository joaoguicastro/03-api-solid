# App

Gympass style app.

## RFs (Requisitos Funcionais)

- [ ] Deve ser possivel se cadastrar;
- [ ] Deve ser possivel se autenticar;
- [ ] Deve ser possivel obter o perfil de um usuario logado;
- [ ] Deve ser possivel obter o numero de ceck-ins realizados pelo usuario logado;
- [ ] Deve ser possivel o usuario buscar academias proximas;
- [ ] Deve ser possivel o usuario buscar academias pelo nome;
- [ ] Deve ser possivel o usuario realizar check-in de uma academia;
- [ ] Deve ser possivel validar o check-in de um usuario;
- [ ] Deve ser possivel cadastar uma academia;

## RNs (Regras de negocio)

-[ ] O usuario nao deve poder se cadastrar com um e-mail duplicado -[ ] O usuario nao pode fazer 2 check-ins no mesmo dia; -[ ] O usuario nao pode fazer check-in se nao estiver perto (100m) da academia; -[ ] O check-in so pode ser validado por admnistradores; -[ ] A academia so pode ser cadastrada por administradores

## RNFs(Requesitos nao funcionais)

-[ ] A senha do usuario precisa estar criptografada -[ ] Os dados da aplicaçao precisam estar persistidos em um banco PostgreSQL -[ ] Todas listas de dados precisam estar paginadas com 20 itens por pagina -[ ] O usuario deve ser identificado po um JWT(json web token)
