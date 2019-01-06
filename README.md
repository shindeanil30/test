# Instructions

Please follow below instruction to compile and run project

## Complie

```bash
javac -cp . booksales\*.java filereader\*.java model\*.java
```

## Run

```bash
java -cp . booksales.BookSales --books=books.list --sales=sales.list --top_selling_books=2 --top_customers=2 --sales_on_date=2018-08-02
```
