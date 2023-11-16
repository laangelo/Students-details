import java.util.Scanner;
public class StudentsDetails{
public static void main(String[]args){
Scanner object = new Scanner(System.in);
System.out.println("Enter Name , DOB ,Regno ,Course , Unitstaken ,Semester");

String Name = object.nextLine();
int DOB = object.nextInt();
int Regno = object.nextInt();
String Course = object.nextLine();
int Unitstaken = object.nextInt();
int Semester = object.nextInt();

System.out.println("Name is" +Name);
System.out.println("DOB is" +DOB);
System.out.println("Regno is" +Regno);
System.out.println("Course is" +Course);
System.out.println("Units taken is" +Unitstaken);
System.out.println("Semester is" +Semester);
}
}
