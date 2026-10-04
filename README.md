# post-lab6-task
# task 1
#include <stdio.h>
int main() {
int num;
    int total = 50000;
    int count = 0;
    
    while(1){
        printf("enter a num or press 0 to stop ");
    scanf("%d",&num);
if(num> total){
    printf("insufficeient balance");
    break;
}
     else{
         total-=num;
         count ++;
         printf("%d",total);

         if (total == 0){
             printf("your balance is now 0");
         }
     }
    }
}

# task 2

#include <stdio.h>
int main() {
int marks=0,sum=0,count=0,avg;
    
    
    while(1){
       printf("enter the marks between 0 and 100 or neg number to stop");
        scanf("%d",&marks);
        if(marks<0){
            break;
        }
else{
    sum +=marks;
    count++;
    avg = sum/count;
  
}
}
     printf("%d total students\n",count);
    printf("%d avg \n",avg);
    printf("%d",sum);
}

# task 3 
#include <stdio.h>
int main() {
int recharge=0,balance=0,count=0;
    while(1){
        printf("enter the recharge amount");
        scanf("%d",&recharge);
        if(recharge<=0){
            break;
        }else{
            balance+=recharge;
                count ++;
            }
        if(balance>=5000){
                printf(" reached Recharge Limit ");
                break;
            }}
    printf(" total recharge amount %d",balance);
        printf("number of recharge attempt %d",count);
    return 0;}

    # task 4
    #include <stdio.h>
int main() {
int price ,total=0,discount,item=1,count=0;
    while(item==1){
        printf("enter the price of an item ");
        scanf("%d",&price);
             total+=price;
           count ++;
       printf("do you want another item write 1 if yes else write 0 ");
          scanf("%d",&item);  
       }
        if(total>10000){
            discount = total*0.10;
            total-=  discount ; }
printf("total price%d \n",price);
    printf("discount%d \n",discount);
    printf("finalamount%d \n",total);
return 0;}

# task 5
#include <stdio.h>
int main() {
int price ,total=0,discount,item=1,count=0;
    while(item==1){
        printf("enter the price of an item ");
        scanf("%d",&price);
             total+=price;
           count ++;
       printf("do you want another item write 1 if yes else write 0 ");
          scanf("%d",&item);  
       }
        if(total>10000){
            discount = total*0.05;
            total-=  discount ; }
printf("total totalbill%d \n",price);
    printf("discount%d \n",discount);
    printf("finalamount%d \n",total);
return 0;}

# task 6
#include <stdio.h>
int main() {
    int pin, attempts=3,remaining;
for(int i = 0;i<attempts;i++){
    printf("enter the pin \n");
    scanf("%d",&pin);
    if(pin==1234){
        printf("login successful");
       break;
    }else{ remaining= attempts-i-1;
        if(remaining>0){
            printf("incorrect password reamining attempt:%d",remaining);
        }else{
            printf("account locked"); }
        }
    }
    return 0;}

# task 7
#include <stdio.h>
int main() {
   int marks[5];
    for(int i = 0;i<5;i++){
        printf("enter the marks");
        scanf("%d",&marks[i]);  }
    int largest = marks[0];
    for(int i = 0;i<5;i++){
        if(largest<marks[i]){
            largest = marks[i];
        } }
     printf("largest value %d\n",largest); 
    int smallest = marks[0];
    for(int i = 0;i<5;i++){
        if(smallest>marks[i]){
            smallest = marks[i];
        } }
     printf("smallest value %d\n",smallest); 
    int total=0;
    for(int i = 0;i<5;i++){
        total+=marks[i];}
    printf("%d total marks\n",total);
    int avg=0;
    for(int i = 0;i<5;i++){
      avg = total/5; }
      printf("%d average",avg);
return 0;
}
# task 8
#include <stdio.h>
int main() {
    int total=0,discount=0,finalamount=0;
   int prices[5];
   for(int i = 0;i<5;i++){
       printf("enter the prices of product");
       scanf("%d",&prices[i]);
   }
    for(int i = 0;i<5;i++){
       total +=prices[i];
    }
    for(int i = 0;i<5;i++){
        if(total>10000){
            discount=total*0.10;
           finalamount = total-discount;      
        }}
printf("total price %d\n ",total);
        printf("discount %d\n",discount);
        printf("finalamount %d",finalamount);}

        # task 9
        

