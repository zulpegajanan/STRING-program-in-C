#include<stdio.h>
#include<string.h>
int main()
{
    int i,word=1;
    char str[100];
    printf("Enter a string\n");
    gets(str);
    //scanf("%s",str);    
    /*
    we could not use scanf function because it scan only one word.after
 
    one space it will ignore other word that's why output will be 1.
    */
   
    
    for(i=0;i<strlen(str);i++)
    {
        if(str[i]==' ')
        {
            word++;
        }
    }
    printf("%d\n",word);
}
