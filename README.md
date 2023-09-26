rails new bookstore --api  -d postgresql

rails g scaffold book title body:text

Book.create!(title: "book1", body: "book details1")
http://localhost:3000/api/v1/books

npx create-react-app bookable
cd bookable
npm start
 npm i axios