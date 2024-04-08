## Ресурси

- [Operator Overloading in C++](https://www.geeksforgeeks.org/operator-overloading-cpp/)
- [Friend Class and Function in C++](https://www.geeksforgeeks.org/friend-class-function-cpp/)

## Задачи

#### Задача 1

Използвайки [примерното решение](https://www.onlinegdb.com/60hCDTeSH) на задачата от [седмица 4](https://github.com/FMI-2023-2024/CS-OOP-7-Excercises/tree/main/Week-4) - да се напише:
- ре-имплементация на `operator +=` която позволява конкатенацията на вектор в каря на съществуващ вектор (`MyVector & operator+=(MyVector const &)`)
- ре-имплементация на `operator +` която позволява конкатенацията на два вектора (`MyVector operator+(MyVector const &) const`)
- ре-имплементация на `operator ==` която проверява за равенство на два вектора, посредством сравнение на елементите им (`bool operator==(MyVector const &) const`)
- ре-имплементация на `operator []` която позволява достъп/промяна на елемент на вектора по индекс (`int & operator[](size_t)`)
  + ако индексът е отрицателен, то връщаме спрямо последния елемент (индекс -1 връща последния елемент, -2 пред-последния и так. нат.)
  + при невалиден индекс хвърляме грешка
- ре-имплементация на `operator <<` която позволява извеждане на елементите на вектор в [CSV формат](https://en.wikipedia.org/wiki/Comma-separated_values) (`std::ostream & operator<<(std::ostream &, MyVector const &)`)
- ре-имплементация на `operator >>` която позволява въвеждане на елементите на вектор от [CSV формат](https://en.wikipedia.org/wiki/Comma-separated_values) (`std::istream & operator>>(std::istream &, MyVector &)`)

[GitHub Classroom](https://classroom.github.com/a/DoN4mX4D)
