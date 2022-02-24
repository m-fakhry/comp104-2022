# Lecture 1

## Agenda

- What is a programming language
- What is a computer program
- Basic form of C++ program
- Data types
- Variables
- Constants
- Arithmetic Operations
- Assignment Operator
- Type Conversion
- Increment/Decrement Operators
- I/O Operators
- Exercise: Calculate the area and circumference of a circle for a given radius r.

---

We discussed
- What a programming language is

- What a computer program is

- We started with the very basic (incomplete) form of a C++ program
<section>
  <pre><code data-trim data-noescape>
    #include < iostream >
    int  main( ) {
        …;
        …;
    }
  </code></pre>
</section>

- We then started to add additional commands to make the program valid
<section>
  <pre><code data-trim data-noescape>
    int  main( ) {
        …;
        …;
        return 0;
    }
  </code></pre>
</section>

- We explained what a library is, and give an example of `iostream` library.
<section>
  <pre><code data-trim data-noescape>
    #include < iostream >
    int  main( ) {
        …;
        …;
        return 0;
    }
  </code></pre>
</section>

- We explained the `cout` statement
<section>
  <pre><code data-trim data-noescape>
    #include < iostream >
    int  main( ) {
        cout<<10+20;
        return 0;
    }
  </code></pre>
</section>

- and gave two forms of `cout` to print either a string or expression. So, the difference between `cout<<"10+20=";`  and `   cout<<10+20;`

- then, how to merge multiple `cout` statements in one statement. For example, `cout<<"10+20="<<10+20;`

- finally, the delimiter `\n`.
