## Count Vowels

Write a program with a function

```cpp
int equals(int a, int b);
```

which checks whether two given integers are the same. This function must return 1 if they are the same, otherwise 0.

**Example**:

```console
a: 2
b: 3
Result: 0
```

```console
a: 4
b: 4
Result: 1
```

<details>
<summary>Answer in C++</summary>

```cpp
#include <iostream>

using namespace std;

int equals(int a, int b) {

    if(a == b) {
        return 1;
    } else {
        return 0;
    }
}

int main(){

    int a;
    int b;
    int result;

    cout << "a: ";
    cin >> a;
    cout << "b: ";
    cin >> b;

    result = equals(a,b);

    cout << "Result: " << result << endl;
}
```

</details>

#### Difficulty Level

Intermediate

#### Tags

`for` `string`
