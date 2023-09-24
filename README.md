# day_2
第二天学习开始
int main(void)
{
	int score;
	printf("请输入你的分数:");
	scanf_s("%2d\n", &score);
	if (score < 1 || score>100)
	{
		printf("请输入正确的分数");
	}
	else
	{
		if (score >= 90)
			printf("A");
		else
		{
			if (80 <= score < 90)
				printf("B");
			else
			{
				if (70 <= score < 80)
					printf("C");
				else
				{
					if (60 <= score < 70)
						printf("D");
					else
					{
						if (score < 60)
							printf("E");
					}
														
				}
									
			}
				
		}		
		

	}
	return 0;//此种代码为错误示范，第一种条件未实现固直接结束，不会进入第二条件
}
