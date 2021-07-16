# __Anna Kovalevskaya__
#### _Minsk, Belarus_

## __Contact Info__
* __[Telegram](https://t.me/Kovalevskayaaa)__ 
* __Mobile__ +37544 549 61 87
* __Email__ lao7777@ya.ru
* __[GitHub](https://github.com/AnnaKowalewskaja)__ 

## __Summary__ 

### I'm a novice developer. I want to improve my programming skills, because I'm very interested in it. When I do something that involves programming, I really get into it! I really like it when something turns out, but if I see an error, I will definitely figure out what the problem MYSELF.
### *I can ask for help, but I will never ask you to write the code for me.*

## __Skills__
* HTML
* CSS
* JavaScript
* PHP *a little bit*
* Markdown

## __Code examples__
```javascript
class BookList {
			
constructor(allBooks) {
      this.allBooks = allBooks;
      this.currentBook = null;
      this.previousBook = null;
      this.nextBook = allBooks[1];
      this.readBook(allBooks[0]);
      this.readBooksCount = 0;
      this.booksReadInPast = [];

     }
   
  finishCurrentBook(){
     this.currentBook.readDate = new Date();
     this.currentBook.readNow = false;
     
     this.booksReadInPast.push(this.currentBook);
     
     //shift - delete first element
     this.previousBook = this.currentBook;
     this.readBooksCount += 1;
     
     this.allBooks.shift();
     
     if(!this.allBooks.length){
       return;
      }
     
     this.readBook(this.allBooks[0]);
     this.nextBook = this.allBooks[1];
     }
   
  readBook(book){
     this.currentBook = book;
     this.currentBook.readNow = true;
     }
   
  addBook(newBook) {
      this.allBooks.push(newBook);
      }

  getReadBooksCount(){
      return this.readBooksCount;
      }
    
  getUnreadBooksCount(){
      return this.allBooks.length ;
      }
    
  } 


class Book {
  constructor(title, style, author, readNow = false, readDate = null) {
    this.title = title;
    this.style = style;
    this.author = author;
    this.readNow = readNow;
    this.readDate = readDate;
  }
}

const books = [
    new Book('Преступление и наказание', 'Проза', 'Фёдор Достоевский'),
    new Book('1984', 'Проза, Фантастика', 'Джордж Оруэлл'),
    new Book('Властелин колец', 'Фэнтези', 'Джон Рональд Руэл Толкин'),
    new Book('Война и мир', 'Роман-Эпопея', 'Лев Николаевич Толстой'),
    new Book('Алиса в Стране чудес', 'Сказка', 'Льюис Кэрролл')
];

const bookList = new BookList(books);

bookList.addBook(new Book('Скотный двор', 'Притча, сатира, антиутопия', 'Джордж Оруэлл'));
   
console.log("Past, present, future:");
console.log(bookList.previousBook);
console.log(bookList.currentBook);
console.log(bookList.nextBook);

console.log("All read and unread books:");
bookList.finishCurrentBook();
console.log(bookList.booksReadInPast);
console.log(bookList);

console.log(`Count of read books: ${bookList.getReadBooksCount()}`);
console.log(`Count of unread books: ${bookList.getUnreadBooksCount()}`)

```

## __Experience__
### While studying at the University, we studied HTML, CSS, JavaScript, C#, PHP, but these were only small basics. Then I started working as a software engineer and now I can try my skills on a real site _(no one sees it yet)_. I often take free courses on programming and working with image editors.
* __[FlowerShop](https://annakowalewskaja.github.io/FlowerShop/)__ 
## __Education__
### __Belarusian State Pedagogical University named after Maxim Tank__
### Teacher of mathematics and computer science, 2015 - 2019
### __Teach Me Skills__
### Front-End Developer

## __English__
### A2
#### _I'm trying to improve my skill._
### I studied English at school and University. However, I've already forgotten most of it. This summer we went to an English-speaking country and there I was able to practice speaking. Upon arrival, I realized that the language is necessary and bought school textbooks, which I now use to learn English. During the course, I try to use the translator only for unknown words. I make notes from the material in English.
