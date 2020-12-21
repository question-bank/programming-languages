## Sum elements

Write a program to read 7 integer numbers and save them in an array. Print on the output the sum of all elements. Use a loop for read the data and another one for calculating the sum.

**Example**:

```console
2
3
4
1
5
2
1
Total: 18
```

<details>
<summary>Answer in C++</summary>

```cpp
#include <iostream>

using namespace std;

int main(){

    int i;
    int myArray[7];
    int total;

    for (i = 0; i < 7; i++) {
        cin >> myArray[i];
    }

    for (i = 0; i < 7; i++) {
        total = total + myArray[i];
    }

    cout << "Total: "<< total << endl;
}
```

</details>

#### Difficulty Level

Intermediate

#### Tags

`arrays`
