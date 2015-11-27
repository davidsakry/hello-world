//# hello-world
//Just starting out on Github

//I'm really interestded in machine learning.  I'm also really interested in self learning.  c++ is my language.

/*hello world David Sakry*/

#include <iostream>
#include <string>

const void enter() {
  while (std::cin.get() != '\n') {
    std::cout << "press enter to continue \n";
  }
}

int main() {
  std::string hw = "Hello World \n";

  std::cout << hw;
  enter();

  return EXIT_SUCCESS;
}

