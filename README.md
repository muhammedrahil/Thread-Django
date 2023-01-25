# Thread-Django


```
import threading

class ThreadClass(threading.Thread):
    def __init__(self,name):
        self.name = name
        threading.Thread.__init__(self)

    def run(self) -> None:
      ... code ...
      return
      
      
def function_name():
    ThreadClass('name').start()
    return Response({"status": "Success", "message": " Successfully"})
    
```
