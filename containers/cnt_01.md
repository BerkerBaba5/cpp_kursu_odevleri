#### Aşağıdaki C++ programı hakkında yorum yapınız:

+ sentaks hatası
+ tanımsız davranış
+ derleyiciye göre değişir
+ ekrana şunu yazar: 

```
#include <iostream>
#include <vector>

int f() { std::cout << "f"; return 1; }
int g() { std::cout << "g"; return 2; }

void foo(std::vector<int>) {}

int main() 
{
	foo({ f(), g() });
}
```
