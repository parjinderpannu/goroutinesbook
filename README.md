# goroutinesbook
golang.org/pkg/sync
golang.org/pkg/sync (Mutex, RWMutex, WaitGroup)
MUTEX : mutual exculsive lock
go run --race .
Close channel at sending side
if you try to get value on closed channel, you are going to get zero value out  

# final summary
10 msg comming in and 10 msg comming out  
waitgroup to let main when all the workers are done.
mutex to protect the in-memory cache from simultaneous writes and writes & reads happening at same time.
channels to co-ordinate the responses from our go routines to return only one go-routine result out.   
