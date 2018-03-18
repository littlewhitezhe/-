#include<stdio.h>
#include<time.h>
#include<stdlib.h>
void main()
{   int data,guess;
    srand((unsigned)time(NULL));
    data=rand()%5+1;
    printf("你要猜的数字（限1~5）：");
    scanf("%d",&guess);
    if(guess==data)
        printf("猜对了，正确数字为%d!\n",data);
    else
        printf("猜错了，正确数字为%d!\n",data);
}

