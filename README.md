# N-queens-problem

n-queens problem 

Problem Description

在N*N的方格棋盘放置了N个皇后，使得它们不相互攻击（即任意2个皇后不允许处在同一排，同一列，也不允许处在与棋盘边框成45角的斜线上。
你的任务是，对于给定的N，求出有多少种合法的放置方法。

Input

共有若干行，每行一个正整数N≤10，表示棋盘和皇后的数量；如果N=0，表示结束。

Output

共有若干行，每行一个正整数，表示对应输入行的皇后的不同放置数量。

Sample Input

1 8 5 0

Sample Output

1 92 10

代码：

#include<stdio.h>

int a[11]={0,1,0,0,2,10,4,40,92,352,724};

int main()

{

	int n;
  
	while(scanf("%d",&n)&&n)
  
		printf("%d\n",a[n]);
    
}
