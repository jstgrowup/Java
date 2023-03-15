## Taking input from the user

- To take input java has scanner class

```
import java.util.Scanner;
```

```
  public class TakingInput {
    public static void main(String[] args) {
        System.out.println("it works");
        Scanner sc=new Scanner(System.in);
        System.out.println("enter number 1");
        int a=sc.nextInt();
        System.out.println("enter number 2");
        int b=sc.nextInt();
        int sum=a+b;
        System.out.println("the sum of these numbers is");
        System.out.println(sum);
    }
}
```
- Here we are making a new object instance of Scanner class in line 13 witth the same template (Class)
- 
