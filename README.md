# Print-sum-of-n-natural-number
import java.util.Scanner;
class main
{
Public Static void main(String args[])
{
int sum=0;
Scanner sc=new Scanner("System.in");
System.out.print("Enter the n value:");
int n=sc.nextInt();
for(i=0;i<=n;i++)
{
sum=sum+i;
}
System.out.print("The sum is:"+sum);
}
}
