# Cita Scan

A blockchain explorer to cita.

## packages

  - postgresql 9.4 and above
    
## Initial Project

```shell
rails db:create db:migrate

or just

rails db:setup
```

## Running test
```shell
rails test
```

## Run Project
```shell
rails s

# start sync process
rails daemons:sync:start 
# run `rails daemons:sync:stop` to stop it
# run `rails daemons:sync:restart` to restart it
# run `rails daemons:sync:status` to see status
```
