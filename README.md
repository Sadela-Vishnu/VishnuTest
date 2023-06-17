                        PART-A(THEORY)

1Q. total web development=front end development+backend development.

2Q.HTML tags are used to define the content and structure of a web page. They are enclosed in angle brackets and are composed of a tag name and attributes.there are mainly three types.
Formatting tags: The tags are used to format text on a web page. Examples include <b> for bold text, <i> for italic text,<u> for underlined text.

Structural tags: These tags are used to define the structure of a web page. Examples include <html>, <head>,<body>,<article>.

Media tags: These tags are used to embed media content such as images, audio files, and videos into a web page.
 Examples include <image>,<audio>and <video>.
Copy



3Q. React is a very popular JavaScript library for its performance. It smartly does the work when it comes to handling page updates and data binding. But there are many scenarios behind that performance. Virtual DOM is one of them. When there is a change in UI then the DOM updates and the UI must be re-render. for virtual DOM  refresh is not required as we saw in youtube notification example.

This re-rendering is a slow process because CSS is also re-calculated at that time, then the layout must be re-computed, and at the last browser must paint the elements on the screen. For that reason, the concept of Virtual DOM appeared. Let's understand what is actually Virtual DOM.

Virtual DOM is something that represents a copy of the actual DOM. React creates a copy of DOM and renders the UI depending on that DOM. React observes all the changes made in the actual DOM and modifies the virtual DOM only where the changes happened. Then it renders the UI only where the changes happened in the virtual DOM. And the name of this process is diffing. Since the virtual DOM tree is just a JavaScript object that’s why this process is fast.

4Q. The main differences between MySQL and NoSQL are:

1.MySQL is a relational database with tabular design,while NoSQL has a document-based design and is not relational in nature.
2.MySQL has a rigid schema and is not easily scalable,while NoSQL can be easily scaled with their dynamic schema nature.
3.SQL databases are vertically scalable,while NoSQL databases are horizontally scalable.
4.SQL databases are table-based,while NoSQL databases are document,key-value,graph.
5. SQL databases are better for multi row transactions, while NoSQL is better for unstructured data like documents.

5Q. DBMS or Database Management System is a software application used to access, create, and manage databases. With the help of DBMS, you can easily create, retrieve and update data in databases. A DBMS consists of a group of commands to manipulate the database and acts as an interface between the end-users and the database.
the following are a few characteristics of DBMS:
1.To limit the permissions of the users
2.Provide multiple views of the single database schema
3.Facilitates security and removes data redundancy
4.Allows multi-user transaction processing and sharing of data
5.Follows the ACID property
6.Offers both physical and logical data independence


