# golang_note

1) The int, uint, and uintptr types are usually 32 bits wide on 32-bit systems and 64 bits wide on 64-bit systems. 

2) nil is only for boolean type. Use "" for strings

3) fmt.Printf("v is of type %T\n", v)  //print v's type

4) A slice does not store any data, it just describes a section of an underlying array.

   The change to a slice will influnce the relative arrays
