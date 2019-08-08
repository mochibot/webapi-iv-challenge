### Project chosen for deployment:
<https://github.com/mochibot/webapi-iii-challenge>

### Link to deployed app:
<https://penny-first-api.herokuapp.com/>

### API Endpoints:

Users
Request | Endpoint |Description | Required body
---|---|---|---
GET | /api/users |Get all users | none
GET | /api/users/:id |Get a specific user | none
POST | /api/users | Add an user | {name: string}
DELETE | /api/users/:id | Delete an user| none
PUT | /api/users/:id | Update an user | {name: string}

Posts
Request | Endpoint |Description |Required body
---|---|---|---
GET | /api/posts |Get all posts| none
GET | /api/posts/:id |Get a specific post| none
GET | /api/users/:id/posts | Get all posts for a specific user| none
POST | /api/users/:id/posts | Add a post for a specific user | {text: string}
DELETE | /api/posts/:id | Delete a post| none
PUT | /api/posts/:id | Update a post | {text: string}

### Front-end:

Endpoints | Description
---|---
/users | Display a list of all users
/users:id | Display a list of all posts by a specific user