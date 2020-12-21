## Count Vowels

Write a program to count all vowels in a given string. Please consider lower and upper cases.

**Example**:

```console
Word: apple
Vowels: 2
```

```console
Word: HoUsE
Vowels: 3
```

<details>
<summary>Answer in C++</summary>

```cpp
#include <iostream>
#include <cstring>

using namespace std;

int main(){

    int i;
    int total = 0;
    string word;

    cout << "Word: ";
    cin >> word;

    for (i = 0; i < word.length(); i++){

        if (word[i] == 'a' || word[i] == 'A') {
            total++;
        }
        if (word[i] == 'e' || word[i] == 'E') {
            total++;
        }
        if (word[i] == 'i' || word[i] == 'I') {
            total++;
        }
        if (word[i] == 'o' || word[i] == 'O') {
            total++;
        }
        if (word[i] == 'u' || word[i] == 'U') {
            total++;
        }
    }

    cout << "Vowels: " << total << endl;
}
```

</details>

#### Difficulty Level

Intermediate

#### Tags

`for` `string`
