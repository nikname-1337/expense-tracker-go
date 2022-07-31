## A simple implementation of a expense tracker API in GO.
---

Application implements a simple weekly/monthly expense tracker. User can add budgets and expenses, as well as see remaining budget by category.  


Runs on localhost:8080 and allows very basic interactions GET, POST, PATCH requests.

```
curl --header "Content-Type: application/json" \
  --request POST \
  --data @exp1.json \
  http://localhost:8080/expenses?id=3
```
