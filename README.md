# Day-3


🔹 1. Class_Objects/
📁 Folder: Class_Objects/

Covers:
🧱 Class definition

🛠️ Constructors (default & named)

💡 Object instantiation

🔐 Encapsulation with private variables

💡 Sample Code

class Person {
  String name;
  int age;

  Person(this.name, this.age);

  void greet() => print('Hello, I am \$name and I am \$age years old.');
}

void main() {
  var p = Person('Alice', 30);
  p.greet();
}



❗ 2. ExceptionHandling/
📁 Folder: ExceptionHandling/

Covers:
🚨 Try-catch-finally structure

🧱 Custom exception classes

✅ Catching specific exception types

💡 Sample Code

void main() {
  try {
    int result = 100 ~/ 0;
  } catch (e) {
    print('Caught an error: \$e');
  } finally {
    print('This always executes.');
  }
}


🔁 3. Generics/
📁 Folder: Generics/

Covers:
📦 Generic functions

🏗️ Generic classes

🛠️ Type safety with generics

💡 Sample Code

T getFirst<T>(List<T> items) => items.first;

void main() {
  print(getFirst<String>(['hello', 'world']));
  print(getFirst<int>([1, 2, 3]));
}


🧬 4. Mixins/
📁 Folder: Mixins/

Covers:

➕ Defining and using mixins

🧠 Code reuse without inheritance
