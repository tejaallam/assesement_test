# assesement_test#
#include<stdio.h>
#include<time.h>
int main()
{
int no_of_ques=1,total_result=0;
char selection,correct_ans;
clock_t start,end;
double time;
start=clock();
while(no_of_ques<=10)
{
printf("%d",[no_of_ques].question\n");
printf("a.option\n");
printf("b.option\n");
printf("c.option\n");
printf("d.option\n");

if(selection==correct_ans)
{
printf("correct\n");
total_result=total_result+1;
}
else
printf("%c",correct_ans);
no_of_ques++;
}
end=clock();
time=((double)(end-start))/CLOCKS_PER_SEC;
printf("total time taken for quizz:%f",time);

printf("how many correct answers:%d",total_result);
if(total_result>=5)
{
printf("pass\n");
}
else
printf("fail\n");
}







