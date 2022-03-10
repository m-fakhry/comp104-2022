# Assignment 2

1. What is the value of `j` in this program
  <section>
    <pre><code data-trim data-noescape>
      int main()
      {
          int i = 100;
          int j1 = 2 * i / 3 % 4;
          float j2 = 2 * i / 3 % 4;
          int j3 = 2.4 * i / 3 % 4;
          float j4 = 2.4 * i / 3 % 4;
          return 0;
      }
    </code></pre>
  </section>

2. Consider the following program which contains some errors. You may assume that the comments within the program accurately describe the program’s intended behavior.
      <section>
        <pre><code data-trim data-noescape>
          int main()
          {
              int n1, n2, d1; // 1
              // Get two numbers from the user
              cin << n1 << n2; // 2
              // Compute sum of the two numbers
              cout << n1 + n2 << endl; // 3
              // Compute average of the two numbers
              cout << n1+n2/2 << endl; // 4
              // Assign some variables
              d1 = d2 = 0; // 5
              // Compute a quotient
              cout << n1/d1 << endl; // 6
              // Compute a product
              n1*n2 = d1; // 7
              // Print result
              cout << d1 << "\n"; // 8
              return 0
          }
        </code></pre>
      </section>

      - For each line listed in the comments, indicate whether or not a compile-time, run-time, or logic error is present. Not all lines contain an error.

3. What are these escape characters do? Write a program to print out statements and try these escape characters to see their effects.
    - Escape characters (\n, \t, \v, \b, \a)

4. Write a C++ program that receives two **integer** values from the user. The program then should print the sum (addition), difference (subtraction), product (multiplication), quotient (division), and remainder after division (modulus). Your program must use only integers.
    - Can you explain the results it produces for all of these operations?
    - Repeat the above program but instead the program should read two **float** values from the user.
