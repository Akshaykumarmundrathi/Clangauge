#include<stdio.h>
int add(int x){
	if(x<10){return x;
	}else{return (x%10+add(x/10));
	}
	
}
main()

{
	int n;
	printf("enter a  number: ");
	scanf("%d",&n);
printf("%d",add(n));
return 0;
}
