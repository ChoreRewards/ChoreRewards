# Introduction

ChoreRewards is a chore tracker and reward system for parents/children. If the child completes a chore, they get X number of points (decided by the parent) which they can then use to "purchase" items.

## Goals

* Give children a sense of accomplishment, as they will be able to mark their chores as "done"
* Teach the value of money; "should I purchase X now, or save up my points and purchase Y?"

# Set-up instructions

This section describes how to set-up ChoreRewards

* Clone the [db][db] package
    * Run Postgress locally, by running `docker-compose up -d`
    * Run the DB migrations, by running `make run`
* Clone the [backend][backend]
    * Run the backend, by running `make run`

You can now query the backend API using gRPC or HTTP (instructions in the [backend][backend] repo README).


[db]: https://github.com/ChoreRewards/db
[backend]: https://github.com/ChoreRewards/backend
