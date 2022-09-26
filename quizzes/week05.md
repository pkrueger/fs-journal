# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?

<!-- enter you answer in the space below -->

```
C - Create
R - Read
U - Update
D - Delete
```

**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

<!-- enter you answer in the space below -->

```
C - post
R - get
U - put
D - delete
```

**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

<!-- enter you answer in the space below -->

```
Object Relational Mapping. We use mongoose for interacting with MongoDB.
```

**4.** Which two `HTTP` request types include a body?

<!-- enter you answer in the space below -->

```
create - needs data to create
put - needs data to update
```

**5.** In a/an **\_\_\_** coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an **\_\_\_** coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run. Fill in the blanks.

<!-- enter you answer in the space below -->

```
Asynchronous
Synchronous
```

**6.** Fill in the missing piece of this snippet of code.

```js
import ______ from "_______";
let Schema = ________.Schema;
```

<!-- enter you answer in the space below -->

```
import mongoose from "mongoose"
let Schema = mongoose.Schema;
```

**7.** What is middleware?

<!-- enter you answer in the space below -->

```
Security checks put in place server side to prevent access to information without proper authorization.
```

**8.** The **\_\_** pipeline delivers information from the client while the **\_\_** pipeline returns it. Fill in the blanks.

<!-- enter you answer in the space below -->

```
request pipeline
response pipeline
```

**9.**
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

<!-- enter you answer in the space below -->

```
https://someurl.com/api/something?tag=winter
```
