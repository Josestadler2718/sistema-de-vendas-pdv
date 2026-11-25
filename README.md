# Sistema de venda para lojas (PDV)

Este é o projeto em que estou trabalhando agora: um sistema de ponto de venda para lojas, com login de usuários e uma API própria. O código fica num repositório privado, porque o sistema vai ser oferecido para lojas com mensalidade. Aqui eu conto o que ele faz e como estou construindo.

> 🚧 **Em desenvolvimento.** Vou atualizando esta página conforme o projeto avança.

## A ideia

O sistema foi pensado para funcionar **offline** no dia a dia do balcão, então a loja continua vendendo mesmo se a internet cair. O acesso é controlado por uma **licença com mensalidade**, e o sistema tem **termos de uso** próprios para os clientes.

## Como estou construindo

- **Back-end em Python**, com uma API própria e login de usuários.
- **Banco de dados PostgreSQL.**
- **Segurança desde o começo:** o sistema acessa o banco com um usuário de permissões restritas, que só consegue fazer o necessário, e as senhas e configurações sensíveis ficam separadas em variáveis de ambiente (`.env`), fora do código.

## Quer saber mais?

Se você é de uma loja e quer conhecer o sistema, ou é recrutador e quer conversar sobre o projeto, me chama no [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-augusto-stadler/) ou no e-mail joseaugustostadler@outlook.com.

---

Feito por José Augusto, estudante de Ciência da Computação na Unigranrio | Afya.
