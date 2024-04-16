## Verbos HTTP e Operações CRUD
### PT/BR
| Verbo HTTP | CRUD | Coleção Inteira (por exemplo, /clientes) | Item Específico (por exemplo, /clientes/{id}) |
|-----------|------|--------------------------------------|--------------------------------------|
| POST      | Criar | 201 (Criado), cabeçalho 'Location' com link para /clientes/{id} contendo novo ID. | 404 (Não Encontrado), 409 (Conflito) se o recurso já existir. |
| GET       | Ler | 200 (OK), lista de clientes. Use paginação, ordenação e filtragem para navegar em listas grandes. | 200 (OK), cliente único. 404 (Não Encontrado) se o ID não for encontrado ou for inválido. |
| PUT       | Atualizar/Substituir | 405 (Método Não Permitido), a menos que queira atualizar/substituir todos os recursos na coleção inteira. | 200 (OK) ou 204 (Sem Conteúdo). 404 (Não Encontrado) se o ID não for encontrado ou for inválido. |
| PATCH     | Atualizar/Modificar | 405 (Método Não Permitido), a menos que queira modificar a própria coleção. | 200 (OK) ou 204 (Sem Conteúdo). 404 (Não Encontrado) se o ID não for encontrado ou for inválido. |
| DELETE    | Excluir | 405 (Método Não Permitido), a menos que queira excluir toda a coleção — o que geralmente não é desejável. | 200 (OK). 404 (Não Encontrado) se o ID não for encontrado ou for inválido. |

---

Sinta-se à vontade para se conectar comigo no [LinkedIn](https://www.linkedin.com/in/victor-vinicius-2a9166255/).  
Para qualquer consulta, você pode me contatar via e-mail em contatovictorvinicius05@gmail.com.



## HTTP Verbs and CRUD Operations
### EN/US
| HTTP Verb | CRUD | Entire Collection (e.g. /customers) | Specific Item (e.g. /customers/{id}) |
|-----------|------|--------------------------------------|--------------------------------------|
| POST      | Create | 201 (Created), 'Location' header with link to /customers/{id} containing new ID. | 404 (Not Found), 409 (Conflict) if resource already exists. |
| GET       | Read | 200 (OK), list of customers. Use pagination, sorting, and filtering to navigate big lists. | 200 (OK), single customer. 404 (Not Found) if ID not found or invalid. |
| PUT       | Update/Replace | 405 (Method Not Allowed), unless you want to update/replace every resource in the entire collection. | 200 (OK) or 204 (No Content). 404 (Not Found) if ID not found or invalid. |
| PATCH     | Update/Modify | 405 (Method Not Allowed), unless you want to modify the collection itself. | 200 (OK) or 204 (No Content). 404 (Not Found) if ID not found or invalid. |
| DELETE    | Delete | 405 (Method Not Allowed), unless you want to delete the whole collection—not often desirable. | 200 (OK). 404 (Not Found) if ID not found or invalid. |

---

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/victor-vinicius-2a9166255/).  
For any inquiries, you can reach me via email at contatovictorvinicius05@gmail.com.
