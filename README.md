# User Management System API (Ruby on Rails)

**Requests that can be sent**:

### INFORMATION ABOUT YOUR ACCOUNT
* **GET** request at `/account/{id}` finds an account with `id`, and displays it.
* **POST** request at `/account` creates a new account with specified arguments.
* **PUT** request at `/account/{id}` finds the account with the `id` and updates it with specified arguments.
* **DELETE** request at `/account/{id}` finds the account with the `id` and deletes it.

### LOGIN PAGE
* **GET** request at `/login` finds an account and logs in based on arguments passed.

### LOGOUT PAGE
* **GET** request at `/logout` logs out of the current account.