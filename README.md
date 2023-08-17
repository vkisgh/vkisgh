#include<stdio.h>
int main()
{
	int id,ps;
	printf("ente your id: ",id);
	scanf("%d",&id);
	switch(id)
	{
	
		case 1001:puts("enter your pswd: ");
		scanf("%d",&ps);
		switch(ps)
		{
			case 1011: puts(" welcome you login: ");
					break;
            default:puts("invalid your id or pswd");
               break;
        }
        break;
        default:puts("id invalid");
	}
}
