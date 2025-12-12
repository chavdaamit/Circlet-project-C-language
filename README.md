
# C Programs Collection – Pattern & Number Logic

Below is a collection of multiple C programs along with their explanations and **program outputs**. This README is formatted for GitHub.

---

## 📌 Program 1: Mirror Number Pyramid

```c
#include <stdio.h>

int main(){

    int n=5;

    for(int i=1;i<=n;i++){

        for(int  j=1;j<=i;j++){
            printf("%d ",j);
        }

        int spaces=(n-i)*4;
        for(int s=1;s<=spaces;s++){
            printf(" ");
        }

        for(int j=i; j>=1;j--){
            printf("%d ",j);
        }

        printf("\n");
    }

    return 0;
}
```

### ✅ Output

```
1                1
1 2            2 1
1 2 3        3 2 1
1 2 3 4    4 3 2 1
1 2 3 4 5 5 4 3 2 1
```

---

## 📌 Program 2: Increasing Numbers Triangle

```c
#include <stdio.h>

int main(){

    int num=11;

    for(int i=1; i<=4;i++){

        for(int j=1; j<=i;j++){
            printf("%d ",num);
            num++;
        }
        printf("\n");
    }

    return 0;
}
```

### ✅ Output

```
11
12 13
14 15 16
17 18 19 20
```

---

## 📌 Program 3: Number Diamond Pattern

```c
#include <stdio.h>

int main(){

    int n=5;

    for(int i=n; i>=1;i--){

        for(int s=1; s<i;s++ ){
            printf("  ");
        }

        for(int j = i; j<=n;j++ ){
            printf("%d ",j);
        }

        for(int j=n-1; j>=i;j-- ){
            printf("%d ",j);
        }

        printf("\n");
    }

    return 0;
}
```

### ✅ Output

```
        5
      4 5 4
    3 4 5 4 3
  2 3 4 5 4 3 2
1 2 3 4 5 4 3 2 1
```

---

## 📌 Program 4: Binary Alternating Pattern

```c
#include <stdio.h>

int main(){

    for(int  i=5; i>=1; i-- ){

        for(int j=5; j>i;j--){
            printf(" ");
        }

        int value=1;

        for(int k=1; k<=i;k++){
            printf("%d",value);
            value=1-value;
        }

        printf("\n");
    }

    return 0;
}
```

### ✅ Output

```
10101
 1010
  101
   10
    1
```

---

## 📌 Program 5: Right-Aligned Number Staircase

```c
#include <stdio.h>

int main(){

    for (int i=5; i>=1;i--){

        for(int j=1;j<i;j++){
            printf(" ");
        }

        for(int k=i;k<=5;k++){
            printf("%d",k);
        }

        printf("\n");
    }

    return 0;
}
```

### ✅ Output

```
    5
   45
  345
 2345
12345
```

---

## 📌 Program 6: Continuous Increasing Numbers Triangle

```c
#include <stdio.h>

int main(){

    int num=41;

    for(int i=1;i<=5;i++){

        for(int j=0; j<i;j++ ){
            printf("%d ",num+j);
        }
        printf("\n");
        num += i;
    }

    return 0;
}
```

### ✅ Output

```
41
42 43
44 45 46
47 48 49 50
51 52 53 54 55
```

---

## 📌 Program 7: Star Box Pattern

```c
#include <stdio.h>

int main(){

    for(int i=1; i<=5;i++){
        printf("* ");
    }
    printf("\n");

    printf("* ");

    for(int j=1; j<=3;j++){
        printf("  ");
    }

    printf("* \n");

    for(int k=1; k<=5;k++){
        printf("* ");
    }
    printf("\n");

    printf("*\n");
    printf("*\n");

    return 0;
}
```

### ✅ Output

```
* * * * *
*       *
* * * * *
*
*
```


Just tell me! 🚀
