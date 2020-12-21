## Sum 10 first natural numbers

Write a C++ program to find the **sum** of the first 10 natural numbers (consider that the first number is 1).

**Example**:

```console
55
```

<details>
<summary>Answer in C++</summary>

```cpp
#include <iostream>

using namespace std;

int main(){

    int i;
    int sum;

    sum = 0;

    for (i = 1; i<= 10; i++) {
        sum = sum + i;
    }

    cout << sum << endl;
}
```

</details>

#### Difficulty Level

Basic

#### Tags

```for```
