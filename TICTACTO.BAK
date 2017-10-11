#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
#include<math.h>
int cwinmove(int a[3][3])
{
int i,k=0;
if(a[0][0]+a[0][1]+a[0][2]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[0][i]==0)
	{a[0][i]=4;
	k=1;}
}}

if(a[1][0]+a[1][1]+a[1][2]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[1][i]==0)
	{a[1][i]=4;
	k=1;}
}}

if(a[2][0]+a[2][1]+a[2][2]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[2][i]==0)
	{a[2][i]=4;
	k=1;}
}}


if(a[0][0]+a[1][0]+a[2][0]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[i][0]==0)
	{a[i][0]=4;
	k=1;}
}}

if(a[0][1]+a[1][1]+a[2][1]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[i][1]==0)
	{a[i][1]=4;
	k=1;}
}}


if(a[0][2]+a[1][2]+a[2][2]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[i][2]==0)
	{a[i][2]=4;
	k=1;}
}}

if(a[0][0]+a[1][1]+a[2][2]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[i][i]==0)
	{a[i][i]=4;
	k=1;}
}}

if(a[0][2]+a[1][1]+a[2][0]==8 && k==0)
{
for(i=0;i<3;i++)
{if(a[i][2-i]==0)
	{a[i][2-i]=4;
	k=1;}
}}
return k;
}

int endwidtie(int a[3][3])
{int i,j,k=1;
 for(i=0;i<=2;i++)
 {for(j=0;j<=2;j++)
	{if(a[i][j]==0)
		{k=0;
		break;}
	}
 }
return k;
}


int secmove(int a[3][3])
{
int i,k=0;
if((a[0][0]+a[0][1]+a[0][2]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[0][i]==0)
	{a[0][i]=4;
	k=1;}
}}

if((a[1][0]+a[1][1]+a[1][2]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[1][i]==0)
	{a[1][i]=4;
	k=1;}
}}

if((a[2][0]+a[2][1]+a[2][2]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[2][i]==0)
	{a[2][i]=4;
	k=1;}
}}


if((a[0][0]+a[1][0]+a[2][0]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[i][0]==0)
	{a[i][0]=4;
	k=1;}
}}

if((a[0][1]+a[1][1]+a[2][1]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[i][1]==0)
	{a[i][1]=4;
	k=1;}
}}


if((a[0][2]+a[1][2]+a[2][2]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[i][2]==0)
	{a[i][2]=4;
	k=1;}
}}

if((a[0][0]+a[1][1]+a[2][2]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[i][i]==0)
	{a[i][i]=4;
	k=1;}
}}

if((a[0][2]+a[1][1]+a[2][0]==2) && k==0)
{
for(i=0;i<3;i++)
{if(a[i][2-i]==0)
	{a[i][2-i]=4;
	k=1;}
}
}
return k;
}

void rmove(int a[3][3], char c)
{
int i,j,v,g;
int s[8];
if(a[1][1]==0)
	{a[1][1]=4;
	 return;}
else{
for(i=0;i<3;i++)
	{for(j=0;j<3;j++)
		{if(a[i][j]==0)
			{a[i][j]=1;
			 s[0]=a[0][0]+a[0][1]+a[0][2];
			 s[1]=a[1][0]+a[1][1]+a[1][2];
			 s[2]=a[2][0]+a[2][1]+a[2][2];
			 s[3]=a[0][0]+a[1][0]+a[2][0];
			 s[4]=a[0][1]+a[1][1]+a[2][1];
			 s[5]=a[0][2]+a[1][2]+a[2][2];
			 s[6]=a[0][0]+a[1][1]+a[2][2];
			 s[7]=a[0][2]+a[1][1]+a[2][0];
			 for(v=0;v<=7;v++)
				{for(g=v+1;g<=7;g++)
					{if (s[v]==2 && s[g]==2)
						{a[i][j]=4;
						 return;}
					 else{a[i][j]=0;}
					}
				}
			 }
		}
	}
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
{
if(a[i][j]==0)
	{a[i][j]=4;
	 return;}
}
}
}
}

int smove(int a[3][3],char c)
{
int i,j,v,g,q=0;
int s[8];
if(a[0][0]==0 && c=='N')
	{a[0][0]=4;
	 q=1;
	 return q;}
else{
for(i=0;i<3;i++)
	{for(j=0;j<3;j++)
		{if(a[i][j]==0)
			{a[i][j]=4;
			 s[0]=a[0][0]+a[0][1]+a[0][2];
			 s[1]=a[1][0]+a[1][1]+a[1][2];
			 s[2]=a[2][0]+a[2][1]+a[2][2];
			 s[3]=a[0][0]+a[1][0]+a[2][0];
			 s[4]=a[0][1]+a[1][1]+a[2][1];
			 s[5]=a[0][2]+a[1][2]+a[2][2];
			 s[6]=a[0][0]+a[1][1]+a[2][2];
			 s[7]=a[0][2]+a[1][1]+a[2][0];
			 for(v=0;v<=7;v++)
				{for(g=v+1;g<=7;g++)
					{if (s[v]==8 && s[g]==8)
						{a[i][j]=4;
						 q=1;
						 return q;}
					 else{a[i][j]=0;}
					}
				}
			 }
		}
	}
}
return q;
}


void main()
{
int a[3][3]={0},i,j,k,t=0,p=0,m,n,s,q=0;
char c;
clrscr();
printf("Do You Wanna Play First?\nReply Y/N\n");
scanf("%c",&c);


if(c=='Y')
{while(t==0 || p==0 || m==5)
{
printf("Your Move.Enter the index\nPress  5 and 5 to exit\n");
scanf("%d%d",&m,&n);
if(a[m][n]==1 || a[m][n]==4)
{printf("Wrong Move\n");
 printf("Computer Wins\n");
 break;}
else
{a[m][n]=1;}

printf("Current TicTacToe\n\n");
for(i=0;i<=2;i++)
{for(j=0;j<=2;j++)
{if(a[i][j]==1)
	{printf("O\t");}
 if(a[i][j]==0)
	{printf("-\t");}
 if(a[i][j]==4)
	{printf("X\t");}
}
printf("\n");
}
t=endwidtie(a);
if(t==1)
{printf("Game Tied\n");
 break;}
if((a[0][0]+a[0][1]+a[0][2]==3) ||(a[1][0]+a[1][1]+a[1][2]==3) ||(a[2][0]+a[2][1]+a[2][2]==3) ||(a[0][0]+a[1][0]+a[2][0]==3) ||(a[0][1]+a[1][1]+a[2][1]==3) ||(a[0][2]+a[1][2]+a[2][2]==3) ||(a[0][0]+a[1][1]+a[2][2]==3) ||(a[0][2]+a[1][1]+a[2][0]==3))
{printf("Human wins\n");
 break;}

printf("Computer Moves\n");
if(t==0)
{p=cwinmove(a);}
if(p==0 && t==0)
{s=secmove(a);}
if(p==0 && t==0 && s==0)
{q=smove(a,c);}
if(p==0 && t==0 && s==0 && q==0)
{rmove(a,c);}
printf("Current TicTacToe\n\n");
for(i=0;i<=2;i++)
{for(j=0;j<=2;j++)
{if(a[i][j]==1)
	{printf("O\t");}
 if(a[i][j]==0)
	{printf("-\t");}
 if(a[i][j]==4)
	{printf("X\t");}
}
printf("\n");
}
if(p==1)
{printf("Computer Wins\n");
break;}

}
}

else if(c=='N')
{while(t==0 || p==0)
{
printf("Computer Moves\n");

if(t==0)
{p=cwinmove(a);}
if(p==0 && t==0)
{s=secmove(a);}
if(p==0 && t==0 && s==0)
{q=smove(a,c);}
if(p==0 && t==0 && s==0 && q==0)
{rmove(a,c);}
printf("Current TicTacToe\n");
for(i=0;i<=2;i++)
{for(j=0;j<=2;j++)
{if(a[i][j]==1)
	{printf("O\t");}
 if(a[i][j]==0)
	{printf("-\t");}
 if(a[i][j]==4)
	{printf("X\t");}
}
printf("\n");
}
if(p==1)
{printf("Computer Wins\n");
break;}
t=endwidtie(a);
if(t==1)
{printf("Game Tied\n");
 break;}

printf("Your Move.Enter the index\n");
scanf("%d%d",&m,&n);
if(a[m][n]==1 || a[m][n]==4)
	{printf("Wrong Move\n");
	 printf("Computer Wins\n");
	 break;}
else
{a[m][n]=1;}
printf("Current TicTacToe\n\n");
for(i=0;i<=2;i++)
{for(j=0;j<=2;j++)
{if(a[i][j]==1)
	{printf("O\t");}
 if(a[i][j]==0)
	{printf("-\t");}
 if(a[i][j]==4)
	{printf("X\t");}
}
printf("\n");
}

if((a[0][0]+a[0][1]+a[0][2]==3) ||(a[1][0]+a[1][1]+a[1][2]==3) ||(a[2][0]+a[2][1]+a[2][2]==3) ||(a[0][0]+a[1][0]+a[2][0]==3) ||(a[0][1]+a[1][1]+a[2][1]==3) ||(a[0][2]+a[1][2]+a[2][2]==3) ||(a[0][0]+a[1][1]+a[2][2]==3) ||(a[0][2]+a[1][1]+a[2][0]==3))
{printf("Human wins\n");
 break;}


}
}



getch();
}