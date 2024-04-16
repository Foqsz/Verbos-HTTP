## HTTP Verbs and CRUD Operations

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
