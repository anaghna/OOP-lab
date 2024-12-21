import java.util.Scanner;
class DoublyLinkedList
{
 Node head = null;
 class Node
 {
  int data;
  Node next;
  Node prev;
  public Node(int data)
  {
   this.data = data;
   this.next = null;
   this.prev = null;
  }
 }
public void insert(int data)
{
  Node temp = new Node(data);
  if(head == null)
  {
   head = temp;
   Node ptr = head;
   while(ptr.next != null)
   {
     ptr = ptr.next;
   }
   ptr.next = temp;
   temp.prev = ptr;
  }
  System.out.print("Data enterd is: "+data);
}
public void delete()
{
 if(head == null)
 {
  System.out.print("List is empty");
 }
 else
 {
  int data = head.data;
  head = head.next;
  head.prev = null;
  System.out.print("Data deleted is : "+data);
 }
}
int data = head.data;
head = head.next;
head.prev = null;
System.out.print("Data deleted is : "+data);
public void display()
{
  Node temp = head;
  if(head == null)
  {
    System.out.print("List is empty");
  }
else
{
 while(temp != null)
 {
  System.out.print(temp.data+" ");
  temp = temp.next;
 }
 }
 }
}
public classlinkedlist
{
 public static void main(String args[])
 {
  DoublyLinkedList dll = new DoublyLinkedList();
  int opt = 0;
  while(opt != 4);
  {
   System.out.print("1. Inser at end");
   System.out.print("\n2. Delete at front");
   System.out.print("\n3. Display linked list");
   System.out.print("\n4. Exit");
   System.out.print("\nEnter your choice : ");
   Scanner sc = new Scanner(System.in);
   opt = sc.nextInt();
   switch(opt)
   {
    case 1:
    {
     System.out.print("Enter the element : ");
     int data = sc.nextInt();
    dll.insert(data);
    break;
   }
   case 2:
   {
    dll.delete();
    break;
   }
   case 3:
   {
    dll.display();
    break;
   }
   case 4:
   {
     break;
  }
  default:
  {
   System.out.print("Invalid choice");
   break;
   }
  }
  }
 }
}
