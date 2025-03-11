#include <stdio.h>

int main() {
    int i,j,n,m;
    printf("enter the row of the matrix:");
    scanf("%d",&n);
     printf("enter the row of the matrix:");
    scanf("%d",&m);
    for(int i=1;i<=n;i++)
    {
      for(int j=1;j<=m;j++)
      {
          printf("&\t");
      }
      printf("\n");
    }
    return 0;
}
