# todo-app

## Environment variables

### `.env`

`VUE_APP_API_URL=XXX`

## Project setup

```
yarn install
```

### Make sure you use the OpenAPI-Backend from the Module 295 (Moodle-ZLI)

Edit the .env file and change the `VUE_APP_API_URL` to the URL of the Backend

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Run your unit tests

```
yarn test:unit
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## Manual test cases

- Without any login, you should see the Register and Login button

  ![login_register](assets/img/login_register.png)

- Logged in, you should see the Log out button

  ![logout](assets/img/logout.png)

- You should see the todos as well

  ![todos](assets/img/todos.png)

- Pressing the "Toggle dark mode" button, it should switch between dark/light mode

  ![darklight](assets/img/darklight.png)

- By pressing the "delete" button, the todo should be deleted

  ![deleted](assets/img/deleted.png)

- By pressing the "edit" button, a dialog should pop up and the todo can be successfully edited

  ![edit1](assets/img/edit1.png)
  ![edit2](assets/img/edit2.png)

- The same should be happening with the "add" button

  ![add1](assets/img/add1.png)
  ![add2](assets/img/add2.png)

- By entering a empty description, this error should pop up

  ![error1](assets/img/error1.png)
