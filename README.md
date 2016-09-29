# golang_note

* The int, uint, and uintptr types are usually 32 bits wide on 32-bit systems and 64 bits wide on 64-bit systems.   
* nil is only for boolean type. Use "" for strings  
* fmt.Printf("v is of type %T\n", v)  //print v's type  
* A slice does not store any data, it just describes a section of an underlying array.  
  The change to a slice will influnce the relative arrays  
* new(something) : create a 0 filled something and return a pointer to it.  
   make(something) : create a something with specified length and return something (not a pointer). make() is only used for slice/channel/map  
* exec.Command("/bin/sh", "-c", "pwd")  
  * exec.Command() will fork/exec to excute 1st parm.  exec.Command("ls -al") //return could not find command
  
   
