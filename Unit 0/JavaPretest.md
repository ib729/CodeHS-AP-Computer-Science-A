**1. Evaluate the mathematical expression: 18 ÷ 3 + 3 × 3 – 8**

Answer: 7

**2. If x represents the values on the number line colored in blue, which inequality accurately reflects the value of x?**

Answer: x ≤ 8

**3. Melissa will only drink a cup of coffee if she has slept less than 8 hours or she had to wake up before 6 am.
In which of the following cases does Melissa not drink a cup of coffee?**

Answer: Melissa sleeps for 8 hours and wakes up at 7 am

**4. Karel the Dog is instructed to move forward two spaces. Then, if Karel is standing on a ball, Karel will turn left and move forward two spaces. Otherwise, Karel will move forward two spaces. Given the starting point below, where will Karel end up?
Starting Point:**

Answer: D (Karel is pointing upward two blocks above the yellow circle.)

**5. In Ms. Garcia’s computer science class, students receive letter grades based on the following scale.**

| Integer Score         | Letter Grade |
|-----------------------|--------------|
| 92 or above           | A            |
| From 81 to 91         | B            |
| From 72 to 80         | C            |
| 71 or below           | F            |

**Which of the following code segments will assign the correct string grade for a given integer score?**

I.
```java
if (score >= 92)
{
    grade = "A";
}
else if (score >= 81)
{
    grade = "B";
}
else if (score >= 72)
{
    grade = "C";
}
else
{
    grade = "F";
}
```
II.
```java
if (score >= 92)
{
    grade = "A";
}
if (81 <= score <= 91)
{
    grade = "B";
}
if (72 <= score <= 80)
{
    grade = "C";
}
if (score <= 71)
{
    grade = "F";
}
```
III.
```java
if (score >= 92)
{
    grade = "A";
}
if (score <= 91 && score >= 81)
{
    grade = "B";
}
if (score <= 80 && score >= 72)
{
    grade = "C";
}
if (score <= 71)
{
    grade = "F";
}
```

Answer: I and III only

**6. Consider the following program code:**
```java
int x = 5;
int y = 8;
int temp = x;
x = y;
y = temp;
```
**What are the values of x and y as a result of this program code?**

Answer: x has a value of 8, y has a value of 5.

**7. You’re building an e-commerce website. You create a class called Transaction to represent a single purchase on the site.**

**Which of these would not make sense as an instance variable in the Transaction class?**

Answer: private int totalTransactionsToday

**8. Which `for` loop will properly print “good luck” 10 times?**

A
```java
for(int i = 10)
{
     System.out.println("good luck");
}
```
B
```java
for(int i = 0; i < 10; i++)
{
     System.out.println("good luck");
}
```
C
```java
for(int i = 0; i++; i < 10)
{
    System.out.println("good luck");
}
```
D
```java
for(int i = 10; i < 0; i++)
{
    System.out.println("good luck");
}
```

Answer: B

**9. What are parameters?**

Answer: The formal names given to the data that gets passed into a method.

**10. What does this method call return?**
```java
public int doubleInt(int x)
{
    x * 2;
}
```
```java
doubleInt(5);
```

Answer: This method is improperly written.

**11. What is the output of the following program?**
```java
public class Main
{
    private String str = "dog";

   /*Use public static void main() to replace the line below   
      outside of the CodeHS platform.*/
    public void run() 
    {
        Main m = new Main("cat");
        System.out.println(m.getString());
    }

    public Main(String str)
    {
        str = str;
    }

    public String getString()
    {
        return str;
    }
}
```

Answer: dog

**12. Based on this code snippet**
```java
public class Shape
{
   public String getShapeName()
   {
       return "Shape";
   }
}

public class Rectangle extends Shape
{
   public String getShapeName()
   {
       return "Rectangle";
   }
}

public class Square extends Rectangle {}

public class Oval extends Shape
{
    public String getShapeName() 
    {
        return "Oval";
    }
}

public class Circle extends Oval
{
    public String getShapeName()
    {
        return "Circle";
    }
}
```
**What does this program output?**
```java
Shape shape1 = new Shape();
Shape shape2 = new Rectangle();
Shape shape3 = new Square();
Shape shape4 = new Circle();

System.out.print(shape1.getShapeName());
System.out.print(shape2.getShapeName());
System.out.print(shape3.getShapeName());
System.out.print(shape4.getShapeName());
```

Answer: Shape Rectangle Rectangle Circle

**13. Which of the following are valid arrays?**
```java
I.   int[] coolArray = {1, 2, 3};
II.  int[] threeThings = {1.0, 2.0, 3.0};
III. int[] = {"1", "2", "3"};
```

Answer: I only

**14. What value will be held in mysteryNumber when this code finishes running?**
```java
int mysteryNumber = 0;
String[] mysteryArray = {"Finn", "Jake", "Bubblegum"};
for(int i = 0; i < mysteryArray.length; i++)
{
    mysteryNumber += mysteryArray[i].length();
}
```

Answer: 17

**15. Given this array:**
```
1 2 4 5 6 7 8 12 14 21 22 42 53
```
**How many comparisons are required to find 42 using the Binary Search?**

Answer: 3
