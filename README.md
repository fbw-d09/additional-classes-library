
# Mini Library :blue_book: :open_book::notebook_with_decorative_cover::orange_book:


Your task is to create a Book class representing a library.

1. Book
Write a Book class that should have 4 properties

- a title as a string
- an author as a string
- an isbn as a number
- isCurrentlyAvailable as a boolean (true as a default value)

The constructor should take 3 parameters initializing those properties. For example


```js
 const atomicHabbits = new Book("Atomic Habbits", "James Clear", 87254612)
 const steveJobs = new Book("Steve Jobs Biography", "Walter Isaacson", 5561246)
```
---

The class should also have a method called `isBookAvailable()`

```js
atomicHabbits.isBookAvailable() //Atomic Habbits is currently available.
```

---

### Bonus 

- try to add a Customer class
- think about properties the customer class could have
- maybe you would also like to add some private fields for personal details in the customer class?
- you could check, if the book, which the customer intends to lend, is an instance of the book class
- when the book has been lend out to the customer, the property `isCurrentlyAvailable` would change to `false`


Happy Coding! :keyboard::woman_technologist::man_technologist:





