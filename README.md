# ToDo_list

## To install
```
npm install todo_list9
```
### A simple use of toDo list
```javascript
  var fake = require('todo_list9');
  fake.addToDo('Play', 'at the park', true, 'andrea');
        fake.addToDo('Hello', 'while you run', true, 'marco');
        fake.addToDo('Trip', 'go at the beach', true, 'salvatore');
fake.deleteToDoById(1);
fake.editToDoStatusById(1, false);
fake.findToDoByUser('salvatore');
fake.readToDoComplete();// return a list toDo completed 
fake.getUsers(); // array of user 
fake.getToDo(); // array of toDo list
fake.reset(); // array of Tweets = []
fake.count(); // array.length of oDo list
```