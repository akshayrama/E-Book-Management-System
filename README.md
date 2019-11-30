# E-Book-Management-System
This is a repository containing code corresponding to an E-Book Management System built as an Object Oriented Analysis and Design project.
This system provides an option of logging in as an Administrator, Customer or a Vendor. The administrator can add books, delete books and 
view other details. A customer can rent or buy books. A vendor would be able to donate books to the library.

The key feature of this E-Book Management System is that one is able to verify the authenticity of the book. The customer, before renting or
buying a book, can make sure that the book is not tampered by a third-party. This is done by reading the lines of the PDF file and translating it
into its equivalent **SHA256** hash code. If the contents of the PDF file is altered, it will be reflected by a change in its hash code which would help us
help to identify tampering. 

![Image of Integrity Checking](https://github.com/akshayrama/E-Book-Management-System/blob/master/ebookimg.png)

The administrator can also upload books and these can be viewed directly from the system.

![Image of Book Viewing](https://github.com/akshayrama/E-Book-Management-System/blob/master/ebookimg1.png)

![Image of uploading](https://github.com/akshayrama/E-Book-Management-System/blob/master/ebookimg2.png)
