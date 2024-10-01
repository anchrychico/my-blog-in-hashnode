---
title: "Activity 17: Data Structure Again"
datePublished: Tue Oct 01 2024 10:52:45 GMT+0000 (Coordinated Universal Time)
cuid: cm1qbkxqk001c09lfczmu38et
slug: activity-17-data-structure-again

---

The goal of this activity is to help you understand the key differences between three important data structures: List, Object, and List of Objects. This activity requires no coding; it is purely focused on comprehension of these concepts.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727777213275/05798606-fc39-4b57-9e95-538ca68cfbc2.jpeg align="center")

1\. **List**

A list (also called an array in some languages) is an ordered collection of elements. It can hold a collection of items, such as names or numbers.

Example in the Table:If we only focus on the product names, the data forms a list.

```plaintext
["Laptop", "Desk Chair", "Smart watch", "Notebook", "Running Shoes"]
```

This is a simple list of product names. It doesn't provide other details about the products, but it keeps them in an ordered sequence.

2\. **Object**

An object is a data structure that holds properties and values. Each object is made up of key-value pairs, where each key is associated with a specific value.

**Example in the Table**:

Each row in the table is an object, where the keys are the column names (ID, Name, Category, Price, Stock, Supplier Email) and the values are the data for each product.

Example of an Object:

{

id: 1,

name: "Laptop",

category: "Electronics",

price: 750,

stock: 50,

Supplier email: "supplier@gmail.com"

}

This object describes a single product (Laptop) with its properties like id, name, category, price, stock, and Supplier email.

**3\. List of Objects**

A list of objects is a combination of both data structures. It is a list (array) where each element in the list is an object. Each object contains detailed information about an entity (like a product).

Example in the Table:

The entire table represents a list of objects, where each row (product) is an object

\[

{

id: 1,

name: "Laptop",

category: "Electronics",

price: 750,

stock: 50,

supplierEmail: "supplier1@gmail.com"

},

{

id: 2,

name: "Desk Chair",

category: "Furniture",

price: 100,

stock: 200,

supplierEmail: "supplier2@gmail.com"

},

{

id: 3,

name: "Smartwatch",

category: "Electronics",

price: 200,

stock: 150,

supplierEmail: "supplier3@gmail.com"

},

{

id: 4,

name: "Notebook",

category: "Stationery",

price: 5,

stock: 500,

supplierEmail: "supplier4@gmail.com"

},

{

id: 5,

name: "Running Shoes",

category: "Apparel",

price: 80,

stock: 100,

supplierEmail: "supplier5@gmail.com"

}

\]

This is a list of objects, where each object contains details about a product.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727777949686/09596c1d-0d69-49b9-84a6-8528ce9ce797.jpeg align="center")

**1\. List**

list is an ordered collection of elements, such as strings or numbers. It allows for simple and ordered data storage.

Example from Employee Table:

If we just look at the employee names, it forms a list:

\["John Doe", "Jane Smith", "Mark Johnson", "Lisa Wong", "Paul McDonald"\]

This is a simple list containing just the names of the employees in order.

2\. **Object**

An object is a data structure that holds data in key-value pairs. It describes an individual entity (in this case, an employee).

Example from Employee Table:

Each row can be represented as an object:

{

id: 1,

name: "John Doe",

department: "Sales",

age: 30,

email: "john.doe@company.com"

}

{

id: 1,

name: "John Doe",

department: "Sales",

age: 30,

email: "john.doe@company.com"

}

This object contains all the information related to a single employee (John Doe), including their ID, name, department, age, and email.

**3\. List of Objects**

A list of objects is a collection (list) of multiple objects, where each object holds detailed information about a particular entity.

Example from Employee Table:

The entire employee table is a list of objects, where each employee is represented as an object:

\[

{

id: 1,

name: "John Doe",

department: "Sales",

age: 30,

email: "john.doe@company.com"

},

{

id: 2,

name: "Jane Smith",

department: "Human Resources",

age: 25,

email: "jane.smith@company.com"

},

{

id: 3,

name: "Mark Johnson",

department: "IT",

age: 40,

email: "mark.johnson@company.com"

},

{

id: 4,

name: "Lisa Wong",

department: "Marketing",

age: 28,

email: "lisa.wong@company.com"

},

{

id: 5,

name: "Paul McDonald",

department: "Finance",

age: 35,

email: "paul.mcdonald@company.com"

}

\]

This list of objects stores details about multiple employees, where each object holds the data for one employee.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727778570812/dbe08a51-d651-4b69-9d9a-c468f77e000f.jpeg align="center")

**1\. List**

A list is an ordered collection of elements, which can be a simple data structure containing items like strings or numbers.

Example from the Books Table:

If we take just the book titles, it forms a list:

\["The Great Gatsby", "To Kill a Mockingbird", "1984", "The Catcher in the Rye", "A Brief History of Time"\]

This is a simple list of book titles.

**2\. Object**

An object is a data structure that stores data as key-value pairs, representing one entity like a book.

Example from the Books Table:

Each row in the table can be represented as an object for a specific book. For example, the first book "The Great Gatsby":

{

id: 1,

title: "The Great Gatsby",

author: "F. Scott Fitzgerald",

genre: "Fiction",

publishedYear: 1925,

isbn: "978-0743273565",

stock: 20,

price: 15.99

}

This object holds all the details of one specific book, including its ID, title, author, genre, and so on.

**3\. List of Objects**

A list of objects is a collection where each item is an object that holds detailed information about a specific entity, such as books.

Example from the Books Table:

The entire books table can be seen as a list of objects, with each book represented as an object:

\[

{

id: 1,

title: "The Great Gatsby",

author: "F. Scott Fitzgerald",

genre: "Fiction",

publishedYear: 1925,

isbn: "978-0743273565",

stock: 20,

price: 15.99

},

{

id: 2,

title: "To Kill a Mockingbird",

author: "Harper Lee",

genre: "Fiction",

publishedYear: 1960,

isbn: "978-0060935467",

stock: 35,

price: 10.99

},

{

id: 3,

title: "1984",

author: "George Orwell",

genre: "Dystopian",

publishedYear: 1949,

isbn: "978-0451524935",

stock: 40,

price: 9.99

},

{

id: 4,

title: "The Catcher in the Rye",

author: "J.D. Salinger",

genre: "Fiction",

publishedYear: 1951,

isbn: "978-0316769488",

stock: 25,

price: 8.99

},

{

id: 5,

title: "A Brief History of Time",

author: "Stephen Hawking",

genre: "Non-fiction",

publishedYear: 1988,

isbn: "978-0553380163",

stock: 10

price: 18.99

}

\]

This list of objects holds detailed information for each book in the list.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727779028448/63f3485c-3e36-4055-a4d0-78f0905a8966.jpeg align="center")

**1\. List**

A list is an ordered collection of items.

Example from the University Table:

If we take just the names of the universities, it forms a list:

\["University of the Philippines", "Ateneo de Manila University", "De La Salle University", "University of Santo Tomas", "Polytechnic University of the Philippines"\]

This is a simple list of university names.

**2\. Object**

An object is a data structure that contains key-value pairs, representing a single entity.

Example from the University Table:

Each row in the table can be represented as an object for a specific university. For example, the first university "University of the Philippines":

{

id: 1,

name: "University of the Philippines",

location: "Quezon City",

establishedYear: 1908,

type: "Public",

website: "www.up.edu.ph"

}

This object holds all the details of one specific university.

**3\. List of Objects**

A list of objects is a collection where each item is an object containing detailed information about a specific entity.

Example from the University Table:

The entire university table can be seen as a list of objects, with each university represented as an object:

\[

{

id: 1,

name: "University of the Philippines",

location: "Quezon City",

establishedYear: 1908,

type: "Public",

website: "www.up.edu.ph"

},

{

id: 2,

name: "Ateneo de Manila University",

location: "Quezon City",

establishedYear: 1859,

type: "Private",

website: "www.ateneo.edu"

},

{

id: 3,

name: "De La Salle University",

location: "Manila",

establishedYear: 1911,

type: "Private",

website: "www.dlsu.edu.ph"

},

{

id: 4,

name: "University of Santo Tomas",

location: "Manila",

establishedYear: 1611,

type: "Private",

website: "www.ust.edu.ph"

},

{

id: 5,

name: "Polytechnic University of the Philippines",

location: "Manila",

establishedYear: 1904,

type: "Public",

website: "www.pup.edu.ph"

}

\]

This list of objects holds detailed information for each university in the list.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727779623122/ff6c1467-e481-468b-9082-8a2767c3aa0e.jpeg align="center")

**1\. List**

A list is an ordered collection of items.

Example from the Restaurant Table:

If we extract just the names of the restaurants, it forms a list:

\["Vikings Luxury Buffet", "Antonio's Restaurant", "Mesa Filipino Moderne", "Manam Comfort Filipino", "Ramen Nagi"\]

This is a simple list of restaurant names.

**2\. Object**

An object is a data structure that contains key-value pairs, representing a single entity.

Example from the Restaurant Table:

Each row in the table can be represented as an object for a specific restaurant. For example, the first restaurant "Vikings Luxury Buffet":

{

id: 1,

name: "Vikings Luxury Buffet",

location: "Pasay City",

cuisineType: "Buffet",

establishedYear: 2011,

website: "www.vikings.ph"

}

This object holds all the details of one specific restaurant.

**3\. List of Objects**

A list of objects is a collection where each item is an object containing detailed information about a specific entity.

\[

{

id: 1,

name: "Vikings Luxury Buffet",

location: "Pasay City",

cuisineType: "Buffet",

establishedYear: 2011,

website: "www.vikings.ph"

},

{

id: 2,

name: "Antonio's Restaurant",

location: "Tagaytay",

cuisineType: "Fine Dining",

establishedYear: 2002,

website: "www.antoniosrestaurant.ph"

},

{

id: 3,

name: "Mesa Filipino Moderne",

location: "Makati City",

cuisineType: "Filipino",

establishedYear: 2009,

website: "www.mesa.ph"

},

{

id: 4,

name: "Manam Comfort Filipino",

location: "Quezon City",

cuisineType: "Filipino",

establishedYear: 2013,

website: "www.manam.ph"

},

{

id: 5,

name: "Ramen Nagi",

location: "Various Locations",

cuisineType: "Japanese",

establishedYear: 2013,

website: "www.ramennagi.com.ph"

}

\]

This list of objects holds detailed information for each restaurant in the list.