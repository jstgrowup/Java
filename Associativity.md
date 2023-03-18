## Associativity in JAVA
# Precedence
```
 int a = 6 * 5 - 34 / 2;
        30-34/2
        30-17
        13
        int b = 6 / 5 - 34 * 2;
        the precedence of * and / are same thats why we see the associativity what is
        coming first from left to right or right to left
        it tells hte ompiler that i am bigger than you are
        12-34*2
        12-68
        56
        here * has the biggest precedence
        left to right is associativity
        highest precedence goes to * and /. They are then evaluated on the basis of
        left to right associativity
        * / ==> left to right associativity
        + - ==> left to right associativity
        ++ = ==> right to left associativity
        System.out.println(a);
        System.out.println(b);
        int k = b * b - (4 * a * c) / (2 * a);
        System.out.println(k);
```
- If the expression is complex than we have to apply brackats to get the correct o/p