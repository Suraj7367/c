# include <stdio.h>

     int main(){
        int num,i,a,b,
        printf("enter starting number:");
        scanf("%d",$a);
        printf("enter the number to stop:");
        scanf("%d";$B);
        FOR (NUM=a;num<=b; num++)
        {
            for(i=2;i<num; i++)
            {
                if(num%i==0)
                break;
            }
            if(i>=num)
            printf("\n%d",num);
        }

        return 0;
     }
