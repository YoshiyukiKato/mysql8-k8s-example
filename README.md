# mysql8-k8s-example

Example codes used in [my dev.to post]().

## usage
### create all resources
```sh
./create
```

### login to mysql server
```sh
$ kubectl exec -it mysql-client /bin/ash
$ mysql -h mysql -u your_user -D your_database -pyour_password

MySQL [your_database]> 
```

### delete all resources
```sh
$ ./delete
```