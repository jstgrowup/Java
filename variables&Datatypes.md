## Anatomy Of A Java Program

- Documentation Section --> Suggested
- Package Statement --> Optional
- Import Statements --> Optional
- Interface Statements --> Optional
- Class Definitions --> Optional
- Main Method Class {
  Main Method Definition }--> Essential
  }

## Data Types In Java

- Primitive Data Type
  - int
  - long
  - double
  - short
  - byte
  - float
  - char
  - bool
- Non Primitive Data Type
  - Later on

# Reserved Keywords

examples like public, static , void etc

```
int tempNumber=8
```

int is datatype and tempNumber is the name of the variable

- Java is a statically typed language

# Primitive Datatype

- byte -> value ranges -128 to 127 and its default value is 0
- short -> default value is 0
- int -> default value is 0
- float -> default value is 0.0f
- long -> takes 8bytes and default value is 0
- double -> default value is 0.0d
- char -> takes 2bytes
- boolean -> default value is false

```
public class One {
    public static void main(String[] args){
        System.out.println("hello world");
        int num1=6;
        int num2=5;
        int num3=7;
        int sum=num1+num2+num3;
        System.out.println(sum);
    }

}
```
