## Ресурси

- [Operator Overloading in C++](https://www.geeksforgeeks.org/operator-overloading-cpp/)
- [Friend Class and Function in C++](https://www.geeksforgeeks.org/friend-class-function-cpp/)

## Задачи

#### Задача 1

Базирайки се на [примерното решение](https://www.onlinegdb.com/60hCDTeSH) на задачата от [седмица 4](https://github.com/FMI-2023-2024/CS-OOP-7-Excercises/tree/main/Week-4) - да се напише клас `MyQueue`. Същият трябва да може да расте наалява динамично (както MyVector) и да имплементира специална версия на следните оператори
- функция `pop` за премахване на елемент от началото (`int pop()`)
- функция `push` за добавяне на елемент в края (`void push(int) const`)
- функция `len` за връщане на текущия брой елементи в опашката (`int len() const`)
- функция `peek` за връщане на текущия връх на опашката, без да го премахва (`int peek() const`)
- ре-имплементация на `operator +=` която позволява добавяне на елемент в края на опашката (`MyQueue& operator+=(MyQueue&, int)`)
- ре-имплементация на `operator ==` която проверява за равенство на две опашки, посредством сравнение на елементите им (`bool operator==(MyQueue const &) const`)
- ре-имплементация на `operator bool` който връща `false` при условие, че опашката няма нито един елемент, `true` във всички останали случаи (`operator bool() const`)
- ре-имплементация на `operator <<` която позволява извеждане на елементите на опашка в [CSV формат](https://en.wikipedia.org/wiki/Comma-separated_values) (`std::ostream & operator<<(std::ostream &, MyQueue const &)`)
- ре-имплементация на `operator >>` която позволява въвеждане на елементите на опашка от [CSV формат](https://en.wikipedia.org/wiki/Comma-separated_values) (`std::istream & operator>>(std::istream &, MyQueue &)`)

[GitHub Classroom](https://classroom.github.com/a/oooXD3Ag)
