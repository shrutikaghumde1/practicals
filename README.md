<!DOCTYPE html>
<html>
<head>
    
    <title>Programming Books for c language</title>
    <script>
        var books = {
            "bookList": [
                {
                    "isbn": "101",
                    "publishdate": "25/02/1989",
                    "publisherhouse": "ram publishers",
                    "edition": "Second",
                    "author": "John mark"
                },
                 {
                    "isbn": "111",
                    "publishdate": "26/05/59",
                    "publisherhouse": "ABC publishers",
                    "edition": "third",
                    "author": "Robert"
                },
                 {
                    "isbn": "121",
                    "publishdate": "28/06/1946",
                    "publisherhouse": "Hindvadi publishers",
                    "edition": "fourth",
                    "author": "Bharat"
                },
                 {
                    "isbn": "131",
                    "publishdate": "22/12/1982",
                    "publisherhouse": "shree ganesh publishers",
                    "edition": "firdt",
                    "author": "rahul"
                },
                 {
                    "isbn": "141",
                    "publishdate": "25/02/1995",
                    "publisherhouse": "jsh publisher",
                    "edition": "Second",
                    "author": "amar"
                },
                {
                    "isbn":"190",
                    "publishdate":"20/5/2000",
                    "publisherhouse":"XYZ publisher",
                    "edition":"first",
                    "author":"raj"
                },
            ]
        };

        function displayBooks() {
            document.write("<h1>Programming Books Collection</h1>");
            for (var i = 0; i < books.bookList.length; i++) {
                var b = books.bookList[i];
                document.write("<h2>" + b.isbn + "</h2>");
                document.write("<p><b>publishdate:</b> " + b.publishdate + "</p>");
                document.write("<p><b>publisherhouse:</b> " + b.publisherhouse + "</p>");
                document.write("<p><b>author:</b> " + b.author + "</p>");
                 document.write("<p><b>isbn:</b> " + b.isbn + "</p>");
                  document.write("<p><b>edition:</b> " + b.edition + "</p>");
                document.write("<hr>");
            }
        }
    </script>
</head>
<body onload="displayBooks()">
</body>
</html>
