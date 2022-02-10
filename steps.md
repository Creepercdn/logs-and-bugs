# Steps

1. Input some part of code:

    ```cpp
    #include <iostream>
    #include <stdint.h>
    using namespace std;
    int main() {
    ```

2. Input "uint64_t":

    ![The things happened](https://github.com/Creepercdn/logs-and-bugs/raw/master/image_1.png)

    It displays 3 options:

    * `uint64_t` (from <stdint.h>)
    * atomic version
    * another `uint64_t` (This option have different icon)

    I select the first.

3. Input the other code:
    ```cpp
        cin >> alpha;
        cout << alpha*alpha << endl;
        return 0;
    }
    ```
