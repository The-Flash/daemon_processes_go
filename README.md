# Daemon Process in Go

This project demonstrates how to start up a daemon(background) process in Go

## Running the program

```sh
go run main.go
```

This will log out the process id of the daemon process

If you are having a hard time killing the process, you can use the following command

```sh
kill -9 [pid]
```

replace `[pid]` with the process id of the Daemon logged out
