# GoldenRazor — Plataforma de Gestão para Barbearias

**GoldenRazor** é uma aplicação completa voltada para barbearias de alto padrão. Com foco em uma experiência fluida e visual sofisticado, o sistema oferece painéis distintos para clientes e barbeiros, cobrindo desde o agendamento de serviços até a administração de usuários — tudo de forma 100% responsiva.

> 💡 Este projeto foi **reconstruído do zero usando Angular**, uma tecnologia moderna e amplamente utilizada no mercado. A versão anterior havia sido feita em JSP com JDBC e MySQL. 
---

## Preview inicial 

![Preview](https://github.com/user-attachments/assets/01bc3302-23cc-4c6f-af7e-a03ee6024c37)


----
## Funcionalidades

### Painel do Cliente

- Autenticação com login e cadastro.
- Edição de dados pessoais (nome, e-mail, telefone).
- Agendamento de Corte, Barba e Corte + Barba.
- Escolha de data e horário com interface intuitiva.
- Visualização de todos os agendamentos.
- Definição e exibição do serviço preferido.
- Scroll suave entre seções e design otimizado para mobile.

### Painel do Barbeiro (Admin)

- Acesso restrito a usuários com perfil de barbeiro.
- Listagem, edição e exclusão de clientes.
- Cadastro de novos barbeiros com controle de permissões.
- Prevenção contra autoexclusão do barbeiro logado.
- CRUD completo com dados persistidos em `localStorage`.

---

## Destaques Técnicos

- Projeto desenvolvido **na raça**, sem uso de frameworks prontos para CRUDs.
- Arquitetura modular e componentes reutilizáveis.
- Persistência com `localStorage` (e opção de integração com JSON Server).
- Visual refinado com SCSS, paleta preta e dourada e UI responsiva.
- Código limpo, legível e pronto para integração futura com APIs reais.

---

## Tecnologias Utilizadas

- **Angular 17**
- **RxJS**
- **SCSS**
- **FontAwesome**
- **LocalStorage**
- **JSON Server** (opcional para testes)

---

## Como Executar

```bash
# Instale as dependências
npm install

# Inicie o servidor Angular
ng serve

# Acesse via navegador
http://localhost:4200

# (Opcional) Para simular API local:
json-server --watch db.json --port 3000

```
---

## Autores

- [@Lipeh011](https://github.com/Lipeh011)  
- [@dev-wallace](https://github.com/dev-wallace)

