# Express-Quests

### Initialisation

1. Clone the repo
2. `cd Express-Quests-03`
3. `npm i`
4. `cp .env.sample .env`
5. `npm run dev`

---

### To validate the quest

_In Postman_

1. In body section, create a user. Don't bother, i've created a template for you. Just copy/paste it and replace values :

```
{
 "firstname":"Michel",
 "lastname" :"Michelle",
 "email":"michel.michelle@michel.michelle",
 "city": "Micheltown",
 "language": "French"
}
```

2. Do a POST request `localhost:5005/api/users/` -> You should have created a user !
