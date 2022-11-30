# gqlgen のチュートリアル

## playground でのクエリ

- Mutation

```
mutation createTodo {
  createTodo(input: { text: "todo", userId: "1" }) {
    user {
      id
    }
    text
    done
  }
}
```

- query

```
query findTodos {
  todos {
    text
    done
    user {
      name
    }
  }
}
```
