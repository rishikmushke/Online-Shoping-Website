#include <stdio.h>
struct item {
int id;
char name[20];
float price;
};
int main() {
struct item a[5] = {
{1,"Mobile",15000},
{2,"Laptop",55000},
{3,"Headphones",2000},
{4,"Watch",3000},
{5,"Keyboard",1500}
};
int choice, qty;
float total = 0;
char address[20];
printf("---- Online Shopping Website ----\n");
printf("Available Items:\n\n");
for(int i = 0; i < 5; i++)
{
printf("%d--%s--Rs.%2.f\n\n",a[i].id,a[i].name,a[i].price);
}
printf("\nEnter Item ID to book: ");
scanf("%d", &choice);
printf("Enter Quantity: ");
scanf("%d", &qty);
for(int i = 0; i < 5; i++)
{
if(a[i].id == choice)
{
total =a[i].price * qty;
printf("\nItem Booked Successfully!\n");
printf("Item Name:%s",a[i].name);
printf("\nPrice:Rs.%.2f",a[i].price);
printf("\nQuantity:%d", qty);
printf("\nTotal Amount:Rs.%.2f", total);
printf("\n\nEnter the address to deliver");
scanf("%s",&address);
printf("\nYour order will be delivered within 3 days");
printf("\n\nyour address is %s",address);
printf("\n\t Thank you for shopping");
}
}
return 0;
}
