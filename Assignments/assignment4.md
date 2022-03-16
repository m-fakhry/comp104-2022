# Assignment 4

1. Read sections 2.2-2.8, 2.10, 3.1-3.4, 3.6-3.10

2. Write a C++ program that requests an integer value from the user. If the value is between 1 and 100 inclusive, print "OK"; otherwise, print "Out of range".

3. Write a C++ program that requests from the user a value representing the month, which is a number between 1 and 12. Then, the program prints the corresponding name of the month. For example, if the user enters 2 the program displays "February". If the number is less than 1 or greater than 12 the program displays an error message.

4. Consider the following section of C++ code:
    <section><pre><code data-trim data-noescape>

    #include <iostream>
    using namespace std;

    int main() {

          int input;
          cin >> input;
          if (input < 10) {
            if (input != 5)
              cout << "wow ";
            else
              input++;
          } else {
            if (input == 17)
              input += 10;
            else
              cout << "whoa ";
          }
          cout << input << endl;
    }

    </pre></code></section>

      - What will the program print if the user provides the following input?

        - (a) 3
        - (b) 21
        - (c) 5
        - (d) 17
        - (e) -5

5. Why does the following section of code always print "ByeHi"?

        int x;
        cin >> x;
        if (x < 0);
          cout << "Bye";
        cout << "Hi" << endl;

6. In each of the following expressions, suppose `a`, `b` and `c` are integer variables that have been assigned the values `a = 3, b = 2 and c =-4`. Determine the value of `y`:
    - `y = a + --b + ++c * a % c ;`
    - `y = 2 * ++b + 3 * ( a-- - c ) ;`
    - `y += a * ++b + c-- * a % c ;`
    - `y *= 4* b + 3 * ( ++a + c ) ; `   
