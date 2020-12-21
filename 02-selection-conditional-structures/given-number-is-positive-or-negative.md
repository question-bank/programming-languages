## Given number is positive or negative

Write a program to check whether a given floating number is positive or negative. Please consider 0 as positive.

**Example**:

```console
Number: 2
Positive
```

```console
Number: -10.2
Negative
```

<details>
<summary>Answer in C++</summary>

```cpp
#include <iostream>

using namespace std;

int main(){

    float number;

    cout << "Number: ";
    cin >> number;

    if (number >= 0) {
        cout << "Positive" <<endl;
    } else {
        cout << "Negative" <<endl;
    }
}
```

</details>

#### Difficulty Level

Beginner

#### Tags

```if``` ```else```
