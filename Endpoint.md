``Versioning: api/v1.0/``

### User Service
- Create: POST: ``api/v1.0/user``
- Update: PUT: ``api/v1.0/user/{id}``
- GetAll: GET: ``api/v1.0/user``
- GetById: GET: ``api/v1.0/user/{id}``
- Delete: DELETE: ``api/v1.0/user/{id}``
- // REST POST: ``api/v1.0/user/{id}``

### AuthService
- To be revisited & also think for Multi-tenancy
- GetToken: POST: ``api/v1.0/Auth``
- AddRole

### Product
- CRUD (Product/Catalog)
- Search to be query-based (GET/POST TBD)

### Inventory
- CRUD
- /report/ - {Model}
- Download report (how to download or export report, do we rerun the report or persist and pull it)

#### Recon Inventory: (bg job)
- Time frame in days (1,7,14,30)
