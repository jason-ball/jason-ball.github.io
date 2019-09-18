**Hello There! My name is Jason and I am a Computer Science student at [Virginia Commonwealth University](https://vcu.edu).**

```c++
#include <iostream>
#include <vector>

int main()
{
    std::vector<char> message;
    message = {'H', 'e', 'l', 'l', 'o', ',', ' ', 'W', 'o', 'r', 'l', 'd', '!', '\n'};
    for (auto &character : message)
    {
        std::cout << character;
    }
    return 0;
}
```
