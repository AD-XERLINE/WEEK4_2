# WEEK4_2
โปรแกรมรายสัปดาห์ที่ 4 อันที่ 2

    #include<stdio.h>


    int main() {

    int a;
    int b;
    int c;


    printf("ENTER 3 NUMBER SUCH AS(6 3 8) : ");
    scanf("%d %d %d",&a,&b,&c);

    if (a-b >=0 && c-b >=0){
	    printf("The smallest number: %d", b);
    }
    else if(b-a >=0 && c-a >=0){
	    printf("The smallest number: %d", a);
    }
    else if(a-c >=0 && b-c >=0){
	    printf("The smallest number: %d", c);
    }

       return 0;
    }
