# COMP346_Assignments

## TODO: ##

* Implement Main class
* Implement Run method in Server Class
* Implement 4 threads
  * Client Class
    * Sending Transaction
    * Recieving Transactions
  * Server Class
  * Network Class
    * Infinite loop that ends when both client threads disconnect
    * if eitehr are still connected -> yield
* All threads execute Thread.Yield() when input / output network buffers are full or empty
* Record the running times of both client threads and server threads using System.currentTimeMillis()
* Output test acses with appropiate running times for client and server threads
* Preform 3 unique runs opf the program and explain the difference in running times

