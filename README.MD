# I ATTACHED THE TWO QUESTIONS IN THIS FILE 


1. # DIFFERENCE BETWEEN HTTP1.1 VS HTTP2

# http1.1

1.	This was released in 1997 and became the Internet Standard. 
2.	This version added many performance enhancements, including keep alive connections, caching mechanisms, request pipelining, transfer encodings, and byte-range requests
3.	 In this process, a client sends a text-based request to a server by calling a method like GET or POST. In response, the server sends a resource like an HTML page back to the client.



4.	The requests and responses will go back and forth between the server and client until the web browser has received all the resources necessary to render the contents of the HTML page on your screen.



5.	There is much to discuss about the lower levels of this stack, but in order to gain a high-level understanding of HTTP/2, you only need to know this abstracted layer model and where HTTP figures into it.

# http2
 

1.	This was Released in February 2015 by the Internet Engineering Task Force (IETF) focussed on improving HTTP performance. 
2.	This article focuses on the significant changes of this version in more detail.

3.	 From the beginning, many browsers supported this standardization effort, including Chrome, Opera, Internet Explorer, and Safari. Due in part to this browser support, there has been a significant adoption rate of the protocol since 2015, with especially high rates among new sites.
4.	 As opposed to HTTP/1.1, which keeps all requests and responses in plain text format, HTTP/2 uses the binary framing layer to encapsulate all messages in binary format, while still maintaining HTTP semantics, such as verbs, methods, and headers.


5.	 An application level API would still create messages in the conventional HTTP formats, but the underlying layer would then convert these messages into binary. This ensures that web applications created before HTTP/2 can continue functioning as normal when interacting with the new protocol.

2. # OBJECT AND ITS INTERNAL REPRESENTATION IN JAVASCIPT


Objects are important data types in javascript. Objects are different than primitive datatypes (i.e. number, string, boolean, etc.). Primitive data types contain one value but Objects can hold many values in form of Key: value pair. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.
Every object has some property associated with some value. These values can be accessed using these properties associated with them.
var myCar = new Object();	
myCar.make = 'Suzuki';
myCar.model = 'Altros';
myCar.year = 1978;
myCar.wheels = 2;
After creating myCar object, the value inside the object can be accessed using keys.
i.e.
myCar.year
Output: 1978
These values can be accessed using brackets notation also.
myCar[year]
Output: 1978
The syntax for adding a property to an object is
ObjectName.ObjectProperty = propertyValue;