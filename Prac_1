Book.java

import java.lang.*;

public class Book {
    private String author;
    private String title;
    private int sheetCounter;

    public Book (String author, String title, int sheetCounter) {
        this.author = author;
        this.title = title;
        this.sheetCounter = sheetCounter;
    }
    public Book (String author, String title) {
        this.author = author;
        this.title = title;
    }
    public Book (String title) {
        this.title = title;
    }

    public void setAuthor (String author) {
        this.author = author;
    }
    public void setTitle (String title) {
        this.title = title;
    }
    public void setSheetCounter (int sheetCounter) {
        this.sheetCounter = sheetCounter;
    }

    public String getAuthor () {
        return author;
    }
    public String getTitle () {
        return title;
    }
    public int getSheetCounter () {
        return sheetCounter;
    }

    public String toString() {
        return author + " wrote " + title + " with " + sheetCounter + " sheets";
    }
}

Library.java

 import java.lang.*;

    public class Library {
        public static void main(String[] args) {
            Book b1 = new Book ("Dmitrii Gluhovskii", "Text", 754);
            Book b2 = new Book ("Ray Bradbury", "451C");
            Book b3 = new Book ("The Witcher");

            System.out.println("Book #2 author is " + b2.getAuthor());
            b3.setAuthor("Andrzej Sapkowski");
            b3.setSheetCounter(1200);
            System.out.println(b3);
        }
    }
