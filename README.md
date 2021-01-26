
### :herb: [Primeiro projeto Spring Boot](https://www.udemy.com/course/java-curso-completo/)
> REST Api para controle de pedidos
<br />

### Modelo de domínio da aplicação
![Camada de domínio](https://raw.githubusercontent.com/miguelarquejada/curso-springboot/master/github-files/domain_model.png)

### :red_circle: Endpoints
* Listar usuários [GET]: _/users_
* Buscar usuário [GET]: _/users/{id}_
* Adicionar usuário [POST]: _/users_ <br />
`{
    "id": 1,
    "name": "Bob Brown",
    "email": "bob@gmail.com",
    "phone": "977557755",
    "password": "123456"
}`
* Deletar usuário [DELETE]: _/users/{id}_
* Atualizar usuário [PUT]: _/users/{id}_ <br />
`{
 "name": "Bob Brown",
 "email": "bob@gmail.com",
 "phone": "977557755"
}`
* Listar pedidos [GET]: /orders_
* Buscar pedido [GET]: _/orders/{id}_
* Listar categorias [GET]: _/categories_
* Buscar categoria [GET]: _/categories/{id}_
* Listas produtos [GET]: _/products_
* Buscar produto [GET]: _/products/{id}_
