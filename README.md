https://inf.ug.edu.pl/~tdz/C/lab-zadania2wer2.pdf

ZAD1
```c
#include <stdio.h>

int main() {

  int tab[]={1,3,7,8,9};
  int i;

  for(i=0;i<=4; i=i+1) printf("tab[%d]=%d\n",i, tab[i]);

  return 0;

  }
```


ZAD2
```c
#include <stdio.h>

int main() {

  int tab[]={1,3,7,8,9};
  int i;

  for(i=4;i>=0; i=i-1) printf("tab[%d]=%d\n",i, tab[i]);

  return 0;

  }
```

ZAD3

```c
#include <stdio.h>

int main() {

  int tab[]={1,3,7,8,9};
  int i,k;
  k=1;

  for(i=0;i<=4; i++)
    {k=k*2;
      tab[i]=k;
printf("tab[%d]=%d\n",i, tab[i]);
    }
  return 0;

  }
```
ZAD4
```c
#include <stdio.h>
int main()
{
    int tab[5], i;
    for(i=0;i<=4;i=i++)
        {
            printf("Podaj wartość dla tab[%d]=", i);
            scanf("%d", &tab[i]);
}
for(i=0;i<=4;i=i+1)
    printf("tab[%d]=%d\n",i, tab[i]);

return 0;
}
```

ZAD5
```c
#include <stdio.h>
int main()
{
    int tab[5], i;
    for(i=0;i<=4;i=i++)
        {
            printf("Podaj wartość dla tab[%d]=", i);
            scanf("%d", &tab[i]);
}
for(i=4;i>=0;i=i-1)
    printf("tab[%d]=%d\n",i, tab[i]);

return 0;
}

```
ZAD6
```c
#include <stdio.h>
int main()
{
    int tab[5], i,suma;
    for(i=0;i<=4;i=i++)
        {
            printf("Podaj wartość dla tab[%d]=", i);
            scanf("%d", &tab[i]);
}
    for(i=4;i>=0;i=i-1){
    printf("tab[%d]=%d\n",i, tab[i]);

    }
    {
suma =tab[0]+tab[1]+tab[2]+tab[3]+tab[4] ;
 printf ("%d \n", suma);
 }


return 0;
}
```
