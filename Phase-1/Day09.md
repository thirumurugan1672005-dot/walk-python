# Important Information
* Strings , Bytes , bytearray
* Strings  and bytes are immutable
* bytearray is mutable

```py
name = "poppins" # string
name = b"poppins" # bytes
name = bytearray(b'poppins') # bytearray
```
* bytes : immutable to make sure the content does not change
* bytearray : used when byte-byte change required

* len(😀) : length of characters present
* len(😀.encode('utf-8')) # length of bytes it encodes


## Unicode
Unicode is the one which represents the characters into integers

UTF-8 is the encoding scheme which will encodes the characters to this

* Actually In Python Unicode is actually number for conveience it was wriiten as hexadecimal
* In RAM Unicode's integer format stored as binary

* In Files Unicode encoded by encoding-formats like UTF-8 encoding
* Files Stored as encoded format
