# Class-and-object
package pkgclass.and.object;

import java.util.Scanner;

class student{

String name;

int age;

int marks;

void inputdetails(){

Scanner sc=new Scanner(System.in);

System.out.println("enter name:");

name=sc.nextLine();

System.out.println("enter age:");

age=sc.nextInt();

System.out.println("enter mark:");

marks=sc.nextInt();

}

void displaydetails(){

System.out.println("name:"+name);

System.out.println("age:"+age);

System.out.println("marks:"+marks);

}

}

public class CLASSANDOBJECT {

/**

* @param args the command line arguments
* public static void main(String[] args) {

student student1=new student();

student1.inputdetails();

student1.displaydetails();

}

}

Output

enter name:

azin

enter age:

18

enter mark:

89

name:azin

age:18

marks:89

BUILD SUCCESSFUL 
