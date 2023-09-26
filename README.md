rails new bookstore --api  -d postgresql

rails g scaffold book title body:text

Book.create!(title: "book1", body: "book details1")