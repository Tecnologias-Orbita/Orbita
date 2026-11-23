# Tables

## Users

| Fields        | Types | Nullable | Key     |
| ------------- | ----- | -------- | ------- |
| id            | text  | no       | primary |
| email         | text  | no       |         |
| display_name  | text  | no       |         |
| password_hash | text  | no       |         |
| created_at    | text  | no       |         |
| updated_at    | text  | no       |         |
## User Sessions

| Fields     | Types | Nullable | Key     |
| ---------- | ----- | -------- | ------- |
| token_hash | text  | no       | primary |
| user_id    | text  | no       | foreign |
| expires_at | int   | no       |         |
| created_at | text  | no       |         |
## Posts

| Fields | Types | Nullable | Key |
| ------ | ----- | -------- | --- |
|        |       |          |     |
