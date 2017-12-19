# dustIn Time Queue Management API

Queue management application

### Version
1.0.0

## Usage

```bash
npm install
```

```bash
npm start
```

## Endpoints
```bash
POST /users/register
```

```bash
POST /users/login   // Gives back a token
```

```bash
GET /users/me         // Needs json web token to authorize
```

```bash
GET /facilities         // Returns facilities array
```

```bash
GET /facilities/:id         // Returns a facility by ID
```

```bash
POST /facilities         // Creates a facility (requires authorization)
```

```bash
PUT /facilities/:id         // Edits a facility by ID (requires authorization)
```

## JSON Format (Schema)
### User
{firstName, lastName, mail, password, role(defaults to 'user')}
### Facility
{name, address, mail, telephone}