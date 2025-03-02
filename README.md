# Тестування та Верифікація Програмного Забезпечення

Цей репозиторій допоможе вам зрозуміти процеси тестування та верифікації програмного забезпечення на прикладі Python, C++ та Go.

## Зміст
1. Вступ до тестування
2. Типи тестів
3. Написання тестів на Python
4. Написання тестів на C++
5. Написання тестів на Go
6. Інструменти для тестування
7. Література

## Вступ до тестування
Тестування є невід'ємною частиною розробки програмного забезпечення, яке допомагає виявити помилки та забезпечити якість продукту.

## Типи тестів
- **Unit Testing**: Тестування окремих модулів або функцій.
- **Integration Testing**: Тестування взаємодії між модулями.
- **System Testing**: Тестування всієї системи в цілому.
- **Acceptance Testing**: Тестування, що перевіряє, чи відповідає система вимогам замовника.

## Написання тестів на Python
### pytest
```python
def test_example():
    assert 1 + 1 == 2
```

## Написання тестів на C++
### Google Test
```cpp
#include <gtest/gtest.h>

TEST(ExampleTest, Addition) {
    ASSERT_EQ(1 + 1, 2);
}
```

## Написання тестів на Go
### testing package
```go
package main

import "testing"

func TestExample(t *testing.T) {
    if 1+1 != 2 {
        t.Error("Expected 1 + 1 to equal 2")
    }
}
```

## Інструменти для тестування
- **Python**: pytest, unittest
- **C++**: Google Test, Catch2
- **Go**: testing, testify

## Література
1. *Software Testing: Principles and Practices* by Srinivasan Desikan and Gopalaswamy Ramesh
2. *The Art of Software Testing* by Glenford J. Myers, Corey Sandler, Tom Badgett

## Про мене
Привіт! Мене звати **Кошнарьов Данил**, я софтвер девелопер та розробник ПО. Моя мета - допомогти вам освоїти тестування та верифікацію програмного забезпечення та стати кращими програмістами.

## Зворотний зв'язок
Якщо у вас є питання чи пропозиції, не соромтеся зв'язатися зі мною.
