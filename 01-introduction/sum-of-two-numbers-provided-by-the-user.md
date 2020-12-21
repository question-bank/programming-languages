## Sum of two numbers provided by the user

Write a program to print on the output the sum of two integer numbers provided by the user.

**Example**:

```console
a = 2
b = 4;
sum = 6
```

<details>
  <summary>Answer in C++</summary>

  ```cpp
    #include <iostream>

    using namespace std;

    int main(){

        int a;
        int b;
        int sum;

        cout << "a = "; 
        cin >> a;
        cout << "b = "; 
        cin >> b;

        sum = a + b;

        cout << sum << endl;

    }
  ```

</details>

#### Difficulty Level

Basic

#### Tags

```introduction```