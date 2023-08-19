---
description: >-
  This is a test Repo to use snippet formatted blocks, markdowns, and general
  integrations to keep tabs on interoperability between GH, GB, and GL
---

# Whiteboard Integer Cross Section: Tab Tester

Repository to be used to form command subject phrasing and general use tooling between the respective GH,GB,GL platforms. The concept in theory, should serve to demonstrate how dynamic their respective interoperability are, as well as how many languages, frameworks, and other applications and integrations can be fit into as concise a space as possible to demonstrate use between the respective platforms.&#x20;

{% tabs %}
{% tab title="First Tab" %}
This is the tab example. Refer to GH once synced for formatting crossover. Basic C++ is the subject. Plug and go fibbonicci is the context.

```cpp
// Some code#include <iostream>

void fibonacci(int terms) {
    long long int t1 = 0, t2 = 1, nextTerm = 0;

    std::cout << "Fibonacci Series: ";

    for (int i = 1; i <= terms; ++i) {
        if(i == 1) {
            std::cout << t1 << ", ";
            continue;
        }
        if(i == 2) {
            std::cout << t2 << ", ";
            continue;
        }
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
        
        std::cout << nextTerm << ", ";
    }
}

int main() {
    int terms;
    std::cout << "Enter number of terms: ";
    std::cin >> terms;

    fibonacci(terms);
    return 0;
}

```
{% endtab %}

{% tab title="Second Tab" %}
This is TabTwo: TBD how tabs can be expanded upon. Basic Python factorial is the subject.&#x20;

```python
// Some codedef factorial(n):
    """Return the factorial of a given number."""
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

if __name__ == "__main__":
    number = int(input("Enter a number to calculate its factorial: "))
    print(f"The factorial of {number} is {factorial(number)}")



```
{% endtab %}
{% endtabs %}
