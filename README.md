# CoTeacher Backend Take Home Project
Take Home Challenge for Backend position CoTeacher

## Task
Design and implement a task list management system using Go programming language. You are free to use any external libs if needed.

In a simplified scenario the task list management system includes the following parts

#### Authenticate
You don't need a proper authentication endpoint.No need to implement authentication, the endpoint can for example assign arbitrary (unique) user id to the client once requested. This user id will be used to make subsequent requests as listed below.

#### Add To Task List
User can send a request with body containing the task list item.
```
{
   user_id: "ID_RETRIEVED_FROM_AUTH_CALL_ABOVE",
   item: "some random item"
}
```

#### Remove From Task List
User can send request to remove an item from the list.
```
{
   user_id: "ID_RETRIEVED_FROM_AUTH_CALL_ABOVE",
   item_id:
}
```

#### Get Task List
User can send request to get all the items in the task list.


## Instructions/Tips
* Return your answer as a zip file containing all relevant files.
* Provide a readable minimalistic implementation that has understandable split to well-named source files and functions.
* Make sure your code runs out of the box.
* You can use memory storage to keep track of the tasks for a user. Don't need to use any DB's.

