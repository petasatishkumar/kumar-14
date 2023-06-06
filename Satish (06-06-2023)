#include<stdio.h>
#define size 10
int stk[size];
int top=-1;
push(int n)
{
	if(top<size-1)
	{
		top++;
		stk[top]=n;
		printf(" %d is Inserted\n",n);
	}
	else
	printf("Stack is full..!\n");
}
pop()
{
	if(top<0)
	printf("\nStack is empty.");
	else
	{
	printf("%d is Deleted\n",top);
	top--;
	}
}
peek()
{
	printf("%d\n",stk[top]);
}
traverse()
{
	int i=0;
	printf("Traverse of elements: \n");
	for(i=0;i<=top;i++)
	printf("%d ",stk[i]);
	printf("\n");
}
main()
{
	int opt,n;
	while(1)
	{
		printf("Stack operations:\n");
		printf("\n1.PUSH");
		printf("\n2.POP");
		printf("\n3.PEEK");
		printf("\n4.TRAVERSE");
		printf("\n5.EXIT\n");
		printf("\nEnter your option: ");
		scanf("%d",&opt);
		if(opt==1)
		{
			printf("\n Enter Element: ");
			scanf("%d",&n);
			push(n);
		}
		if(opt==2)
		{
			pop();
		}
		if(opt==3)
		{
			peek();
		}
		if(opt==4)
		{
			traverse();
		}
		if(opt==5)
		{
			printf("\nTHANK YOU");
			break;
		}
		printf("\n\n");
	}
}
