## Print a Triangle

Write a program to print the following pattern:

```sh
            C
          i   I
        s       s
      b           b
    e               e
  s                   s
t s e b s i C i s b e s t
```

<details>

  <summary>Answer in C++</summary>
  <br/>

  ```cpp
  #include <iostream>

  using namespace std;

  int main(){

      cout << "            C";
      cout << "          i   I";
      cout << "        s       s";
      cout << "      b           b";
      cout << "    e               e";
      cout << "  s                   s";
      cout << "t s e b s i C i s b e s t";

  }
  ```
</details>

<table>
<tr>
<th> Good </th>
<th> Bad </th>
</tr>
<tr>
<td>

```c++
int foo() {
    int result = 4;
    return result;
}
```

</td>
<td>

```c++
int foo() { 
    int x = 4;
    return x;
}
```

</td>
</tr>
</table>



#### Difficulty Level

Beginner

#### Tags

```basic```