- 👋 Hi, I’m @SnehithaCS1028
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SnehithaCS1028/SnehithaCS1028 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Python Program to perform addition of two complex numbers using binary + operator overloading.
class complex:
    def __init__(self, a, b):
        self.a = a
        self.b = b
 
     # adding two objects
    def __add__(self, other):
        return self.a + other.a, self.b + other.b
 
Ob1 = complex(1, 2)
Ob2 = complex(2, 3)
Ob3 = Ob1 + Ob2
print(Ob3)
