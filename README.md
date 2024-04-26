# Book-Hub

<<<<<<< HEAD
# Book-Hub

=======
>>>>>>> f5c6fc8 (first commit)
requirements :

node : v13.14.0
npm : 6.14.4



```text
  username: aakash
  password: sky@007
```

**Note:** Use the below sample code snippet to make a POST request on Login using valid username and password.

  ```js
  const options = {
    method: 'POST',
    body: JSON.stringify(userDetails),
  }
  ```

**Login API**

#### URL: `https://apis.ccbp.in/login`

#### Method: `POST`

#### Description:

Returns a response based on the credentials provided

**Books API**

#### URL: `https://apis.ccbp.in/book-hub/books?shelf={bookshelfName}&search={searchText}`

#### Example: `https://apis.ccbp.in/book-hub/books?shelf=Read&search=Luke`

#### Method: `GET`

#### Description:

Returns a response containing the list of books based on the query parameters

```json
{
  "book_details": {
    "id": "7850622e-1b70-4396-963d-e68d5a2577d7",
    "author_name": "Ady Barkan",
    "cover_pic": "https://assets.ccbp.in/frontend/react-js/eyes-to-the-wind-book.png",
    "about_book": "Eyes to the Wind is a rousing memoir featuring intertwining storylines about determination, perseverance, and how to live a life filled with purpose and intention.",
    "rating": 4.8,
    "read_status": "READ",
    "title": "Eyes to the Wind",
    "about_author": "Ady Barkan is an American lawyer and liberal activist. He is a co-founder of the Be a Hero PAC and is an organizer for the Center for Popular Democracy, where he led the Fed Up campaign."
  }
}
```
