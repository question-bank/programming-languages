## Count number of lines

Write a program to read a file and print on the output the number of lines. As an example, consider:

**File**:

```console
a b
c d
d
```

**Output**:
```console
Total: 3
```

<details>
<summary>Answer in C++</summary>

```cpp
#include <iostream>
#include <fstream>
#include <cstring>

using namespace std;

int main(){

    int total;
    string line;
    fstream file;

    file.open("input.txt", ios::in);

    while (!file.eof()) {
        getline(file, line);
        total++;
    }

    cout << "Total: "<< total << endl;

    file.close();
}
```

</details>

#### Difficulty Level

Intermediate

#### Tags

`files`
