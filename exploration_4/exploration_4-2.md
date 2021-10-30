### 1.

The global keyword marks variables that can be stored and accessed from multiple
sections of a program. It is necessary in this program because variables are not
being passed between methods, so the methods need to access the data globally. 

### 2.

The most clear benefit is that code is now approaching a better level of
organization where the primary task is divided into multiple procedures, such as
filtering characters, but the downside is that important variables, such as data
are declared globally, which can lead to bugs due to poor encapsulation. One way
it could happen is if one of those procedures is called a second time or out of
order.

### 3.

A procedure will change the state of some shared variable, where a function
might take some data and might return some output. A subroutine is some named
piece of code. 

### 4.

The one that prints a string on the screen has a side effect because it is
writing to the screen. A function that changes a global variable also has a side
effect because it is acting on shared data. Side effects are generally not good
becasue they can introduce a lot of bugs.

### 5. 

Mutable. They can not be re-assigned, but data within them can be. The object
itself needs to be made immutable.

### 6.

A POST request is not idempotent because when it is invoked many times, it will
not have different outcomes. This is because POST is used to create a new
resource on the server, so calling it n times will yield n new resources on the
server.

