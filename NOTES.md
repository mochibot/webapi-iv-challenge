### Project chosen for deployment:
<https://github.com/mochibot/webapi-iii-challenge>

### Link to deployed app:
<https://penny-first-api.herokuapp.com/>

### API Endpoints:

##### Users
Request | Path | Description | Required body 
---- | ---- | ---- | ----
GET | /api/users | Get all users | 
GET | /api/users/:id | Get a specific user | 
POST | /api/users | Add an user | {name: string}
DELETE | /api/users/:id | Delete an user| 
PUT | /api/users/:id | Update an user | {name: string}

##### Posts

Request | Path | Description | Required body
----|----|----|----
GET | /api/posts | Get all posts| 
GET | /api/posts/:id | Get a specific post| 
GET | /api/users/:id/posts | Get all posts for a specific user | 
POST | /api/users/:id/posts | Add a post for a specific user | {text: string}
DELETE | /api/posts/:id | Delete a post | none
PUT | /api/posts/:id | Update a post | {text: string}

### Front-end:

Path | Description
---|---
/users | Display a list of all users
/users:id | Display a list of all posts by a specific user
