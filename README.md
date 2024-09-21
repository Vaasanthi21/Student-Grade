# Student-Grade
import java.util.*;
class StudentGrade
{
	public static void main(String[] args)
	{
		Scanner v=new Scanner(System.in);
		System.out.println("Enter the Total Subjects:");
		int n=v.nextInt();
		int arr[];
		arr=new int[n];
		int sum=0;
		for(int i=0;i<n;i++)
		{
			System.out.println("Enter The Marks of Subject["+(i+1)+"]:");
			arr[i]=v.nextInt();
			sum+=arr[i];
		}
		System.out.println("Sum Is:",sum);
		int avg=(sum/n);
		System.out.println("Average is:",avg);
		int perc=avg/100
		if(perc>=90)
		{
			System.out.println("Obtained Grade is: A");
		}
		else if(perc>=80)
		{
			System.out.println("Obtained Grade is: B");
		}
		else if(perc>=60)
		{
			System.out.println("Obtained Grade is: C");
		}
		else if(perc>=40)
		{
			System.out.println("Obtained Grade is: D");
		}
		else
		{
			System.out.println("Obtained Grade is: F");
		}
	}
}
