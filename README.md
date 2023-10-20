Goodreads is an American social cataloging website and a subsidiary of Amazon that allows individuals to search its database of books, annotations, quotes, and reviews. Users can sign up and register books to generate library catalogs and reading lists. They can also create their own groups of book suggestions, surveys, polls, blogs, and discussions.

### Problem statement

* We are going to the genre lists page - https://www.goodreads.com/list?ref=nav_brws_lists
* From the genre lists page selecting each genre titles and its url
* From the particular genre url getting the booklists types, no. of books and no. of voters
* We are going to select a particular genre and download all the books in it

### Project Outline

#### Step 1:

* We're going to scrape Goodreads web site https://www.goodreads.com/list?ref=nav_brws_lists

* We'll get a list of genres and its url first save it to a csv.

* For each genre we'll get different book list types, no. of books and no. of voters.

* For each Genre we got the first 30 book lists with their titles, url with number of books available and voters and saved it to a csv

#### Step 2:

* We selected Fiction Genre and got the first 30 book list types and the first 100 books under each book list type

* Each book will have the book title, Book url, Author, Avg Rating Total ratings, Book score and votes

* Sved it into a csv file

#### Step 3:

* For each booklist type we'll create a CSV file in the following format:

* Format: Book Title,Book url ,Author ,Average rating and Total Ratings ,Bookscore and votes

* Example: Harry Potter series box set,https://www.goodreads.com//book/show/862041.Harry_Potter_Series_Box_Set, J.K Rowling, 4.74 avg rating ‚ 273,511 Total ratings ,score:10,671,and 110 peoplevoted

#### Step 4:

* Getting the description took a lot of time so I took a particular genre Children and took a particular book list Best series under Childrens Genre and got descriptions only for those to save time and saved it into a csv file

#### Step 5:

* Now using while loop and for loop i want to scrape book details from atleast first 3 pages under Childrens Genre and Booklist type: Picture books and save it to a csv file
