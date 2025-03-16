# C-33
Direct recursion 
#include<stdio.h>
void countdown(int n){
	if(n==0){
	printf("countdown finish!!\n");
	return;
    }
    printf("%d\n",n);
    countdown(n-1);
}
int main()
{
	countdown(10);
	return 0;
}                                                                                                                                                        
