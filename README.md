**Hello There! My name is Jason and I am a Computer Science student at [Virginia Commonwealth University](https://vcu.edu).**

```c++
#include <iostream>
#include <vector>

int main(int argc, char **argv)
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
[Run code sample](https://website-code-sample.jasonericball.repl.run)

### Active Projects:
* [cpp-web-server](https://jason-ball.com/cpp-web-server)
  * A **VERY** basic server for serving static content (HTML, CSS, JavaScript, etc.)
* [JASON_BALL_CMSC312_2019](https://github.com/jason-ball/JASON_BALL_CMSC312_2019)
  * CMSC 312 project: Simulating an Operating System
