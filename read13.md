# Read: 13 - Local Storage

 _what is HTML5 Storage?_ 

 Simply put, it’s a way for web pages to store named key/value pairs locally,

 you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript,


 if you are storing and retrieving anything other than strings, you will need to use functions like **parseInt()** or **parseFloat()** to coerce your retrieved data into the expected JavaScript datatype.

 If you want to **keep track** programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
