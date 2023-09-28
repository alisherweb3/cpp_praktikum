algoritm count va count_if

```
const vector<int> xs = {1, 2, 1, 1, 5};
cout << count(xs.begin(), xs.end(), 1) << endl; // 3
```
'''begin''' va '''end''' funksiyalari vektor ustida. algoritm '''count'''.

```
const vector<string> escapes = {
  "cat"s, "dog"s, "parrot"s, "cat"s, "rat"s, "parrot"s, "cat"s, "dog"s
};
cout << count(escapees.begin(), escapees.end(), "parrots"s); // 2 pupes
```

RESERVE algoritmi SORT funksiyasini, vektorda ishlatadi.
```
reverse(xs.begin(), xs.end());
```

ACCUMULATE algoritmi
```
int sum = accumulate(xs.begin(), xs.end(), 0);
```

accumulate algoritmini qanday ishlashini yana ko'rib chiqamiz

```
#include <iostream>
#include <numeric>
#include <vector>

using namespace std;

int main() {
  int size;
  cin >> size;

  vector<int> values:
  for (int i =0; i < size; ++i) {
    int value;
    cin >> value;
    values.push_back(value);
  }

  int sum = accumulate(values.begin(), values.end(), 0);
  cout << sum << endl;
]
```

Ulangan algoritmlar

```
const set<string> menagerie = {"cat"s, "dog"s, "rat"s);
cout << menagerie.count("cat"s) << endl;
cout << count(menagerie.begin(), menagerie.end(), "cat"s) << endl;
// javob
// 1
// 1
```
