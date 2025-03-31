# cli-task-tracker

A CLI task manager created with PHP. https://roadmap.sh/projects/task-tracker

## Usage

```php
# add task
php task-cli add "description"

# update / delete task
php task-cli update 1 "new description"
php task-cli delete 1

# change task status
php task-cli mark-in-progress 1
php task-cli mark-done 1

# listing tasks
php task-cli list
php task-cli list todo
php task-cli list in-progress
php task-cli list done

```
