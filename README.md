# ToDo - API

API made in NodeJS for ToDo - project that allows the user to create tasks and mark them as completed.

## Node and NPM is required

## Installation

* Clone the project with 

```
git clone https://github.com/jvdsantos3/todo-api.git
```

* Run the command

```
npm run dev
```

## Routes

### List Tasks (GET)

* http://localhost:3334/tasks

### Create Task (POST)

* http://localhost:3334/tasks
* Body of the request

```
{
	"title": "Study NodeJS",
	"description": "Study NodeJS"
}
```

### Update Task (PUT)

* http://localhost:3334/tasks/id
* Body of the request

```
{
	"title": "Study NodeJS",
	"description": "Study NodeJS"
}
```

### Delete Task (DELETE)

* http://localhost:3334/tasks/id

### Complete Task (PATCH)

* http://localhost:3334/tasks/id/complete
