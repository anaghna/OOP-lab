import java.util.Scanner;
public class Binarysearch
{
 static int ar[]=new int[50];
 static void Binary(int low,int up,int key)
 {
  int mid;
  int flag=0,index=0;
  while (low<=up)
  {
   mid=(low+up)/2;
   if (ar[mid]==key)
   {
    flag=1;
    index = mid+1;
    break;
   }
   else if (ar[mid]<key)
   {
    low=mid+1;
   }
   else if (ar[mid]>key)
   {
    up=mid-1;
   }
  }
  if (flag==1)
  {
   System.out.println("Element found at position "+index);
  }
  else
  {
    System.out.println("Element not found");
  }
  }
  public static void main(String[] args)
  {
    Scanner sc = new Scanner(System.in);
    int n,l,h;
    System.out.print("Enter the Number of Elements : ");
    n = sc.nextInt();
    l=0;h=n-1;
    System.out.println("Enter "+n+" Elemnts to the array");
    for(int i=0;i<n;i++)
    {
      ar[i]=sc.nextInt();
    }
    System.out.print("Enter Search Element : ");
    int key = sc.nextInt();
    Binary(l,h,key);
    sc.close();
   }
}
