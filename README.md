# AzureCosmosDBTodos

Задание: реализовать CRUD операции для таблицы в базе CosmosDB (с использованием NodeJS)

Таблица Items в базе DBTodos: 

{
    "title": "replace_with_new_document_id",
    "completed": false,
    "id": "3a8b06f6-bf20-4db0-8d94-fd2ea729f405",
    "_rid": "SGpFAMkWxocBAAAAAAAAAA==",
    "_self": "dbs/SGpFAA==/colls/SGpFAMkWxoc=/docs/SGpFAMkWxocBAAAAAAAAAA==/",
    "_etag": "\"c0017277-0000-0700-0000-5fe793bc0000\"",
    "_attachments": "attachments/",
    "_ts": 1609012156
}

С использованием Azure сервиса FunctionApp реализованы 4 операции:

getTodos - получить список книг https://function-crud.azurewebsites.net/api/getTodos?

insertTodos - создать задачу https://function-crud.azurewebsites.net/api/insertBook?

updateTodos - обновить задачу https://function-crud.azurewebsites.net/api/updateTodos?

deleteTodos - удалиить задачу https://function-crud.azurewebsites.net/api/deleteTodos?

