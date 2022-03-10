# Assignment 3

1. Read sections 2.2-2.8, 2.10, 3.1-3.4, 3.6-3.10

2. Consider the following section of C++ code:
    <section><pre><code data-trim data-noescape>
    // i, j, and k are ints
    if (i < j) {
      if (j < k)
        i = j;
      else
        j = k;
    }
    else {
      if (j > k)
        j = i;
      else
        i = k;
    }
    cout << "i = " << i << " j = " << j << " k = " << k << endl;
    </pre></code></section>

      - What will the code print if the variables i, j, and k have the following values?

        - (a) i is 3, j is 5, and k is 7
        - (b) i is 3, j is 7, and k is 5
        - (c) i is 5, j is 3, and k is 7
        - (d) i is 5, j is 7, and k is 3
        - (e) i is 7, j is 3, and k is 5
        - (f) i is 7, j is 5, and k is 3

3. Calculate the following expression:

        int a =3, b=5, c=8, d;
        d = 2*a+(3*a*a >= b*b) - 6*b-10*(b*b < 8*a);
        d = 3*b+(3*a*a >= b*b && 4*a>3*b) - 6*b-10*(b < 8*a);
        d = 3*b*a+(3*b*a >= b*b || 4*a>3*b) - 2*b-10*(b < 8*a);
        d = 3*b+( 9*a > b*b || a >= b*b && 4*a<3*b) - 6*b-10*(b < 8*a);

4. Write a C++ program that requests four integer values from the user. It then prints the maximum and minimum values entered. If the user enters the values 3, 2, 5, and 0, the program would indicate that 5 is the maximum and 0 is the minimum.

5. Write a C++ program that displays a menu to the user with multiple options: (1) Spicy Crispy Chicken Sandwich, (2) Big Mac, and (3) Chicken McNuggets. The user has to choose only one of these three options. Based on the chosen option the program displays the price of the meal. If the user chooses an invalid option, the program displays an error message.
The program should run as follows:
    <span style="background-color:green">
    <section><pre><code data-trim data-noescape>

    Which sandwich you would like to have:
    1- Spicy Crispy Chicken Sandwich
    2- Big Mac
    3- Chicken McNuggets

    Please enter your choice: <span style="color:red">2</span>
    The price for <span style="color:blue">Big Mac</span> is <span style="color:blue">LE80</span>
    </pre></code></section>
    </span>

    Hint: define these options as **enum** type.
