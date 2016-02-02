/*The program then will ask the user to estimate this number. The number of programs with some tips that will help the user to find.
If it guesses correctly the number of users will be given a number and location of the user to +1 point,
if the figures wrong place guessed correctly predicted the user will be given -1 point. The program will continue
until you find the correct number of users. When you find and replace numbers beginning +0 -0 value in and of itself
will increase +0 true value, the figures wrong when you have found the place to find itself right will increase the value -0.
Sample output will be as follows:
Estimate a 3-digit number:
(Assume that the computer produces the number 340)
Estimate: 403
Conclusion: +0 -3
(Because the user has guessed correctly but 4,0 and 3 digits in the wrong place)
Your Estimation: 123
Result: -1 +0
(3 digits because the user has guessed correctly but the location wrong)
Your Estimation: 246
Conclusion: +1 -0
(4 digits because the user guessed the right place)
Your Estimation: 543
Result: -1 +1
(4 digits because the users in the right place, at the wrong place if he guessed the 3 digits)
Your Estimation: 789
Conclusion: +0 -0
(Because users can not predict any figure right)
Your Estimation: 340
*/

#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
#include<stdlib.h>
#include<conio.h>
#include<time.h>
#include <string.h>
 main(){ int i,m,a,b,x,y;

     int olusan [3],tahminSayi[4]; char tahmin[6]; 
	  srand(time(NULL));
aynıİse:
	 for(i=0;i<3;i++) 
      olusan[i]=rand()%10;

     if(olusan[0]==olusan[1] || olusan[0]==olusan[2] || olusan[1]==olusan[2] || olusan[0]==0)
	  goto aynıİse;

tahminAynı:
enBaş:

	  printf("Enter the 3-digit number of different figures: ");
	  scanf("%s",&tahmin);
	 
	 if(strlen( tahmin )!=3)
	  goto tahminAynı;

	 if( tahmin[0]==tahmin[1] || tahmin[0]==tahmin[2] || tahmin[1]==tahmin[2] ){
	  printf("please enter a number of different figures \n");
	   goto tahminAynı; }
	 
	 for(m=0;m<3;m++) {
	  tahminSayi[m]=(((int)tahmin[m])-48);}
	  a=b=0;
	 
	 for(x=0;x<3;x++){
	  for(y=0;y<3;y++){
	   if(olusan[x]==tahminSayi[y]){
		if(x==y)
		  a++;
		else 
		  b++;  } } }
	 
	 if(a==3)
	  printf("congratulations!!!\n");
	 else{
	  printf("result= + %d  - %d \n",a,b);
	  goto enBaş; } }

