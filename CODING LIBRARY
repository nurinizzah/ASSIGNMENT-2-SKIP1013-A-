package code1;

import java.util.Scanner;
public class Library2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		String name, books, date_1, date_2,proceed;
		int Matric_id, age, sem, choice;
		int totalbooks = 10000, fine = 1;
		int fine1, fine2, fine3, fine4, fine5;
		
		
		Scanner sc = new Scanner(System.in);
		System.out.println("Welcome to the University Library Management System.");
		System.out.println("Please enter your personal information to proceed to borrow a book.");
		System.out.print("Please enter your name: ");
		name = sc.nextLine();                                //Students enter their name
		
		System.out.print("Please enter your Matric id: ");
		Matric_id = sc.nextInt();							//Students enter their age
		
		System.out.print("Please enter your age: ");
		age = sc.nextInt();
		
		System.out.print("Please enter your current semester: Semester ");
		sem = sc.nextInt();									//Students enter their current semester
		
		System.out.println(" ");
		
		System.out.println("============================================================================================================================== ");
		
		
		System.out.println("There are  "+totalbooks+" books that students can borrow");
		System.out.println("How many books do you want to borrow? (maximum books that can be borrow = 5)");
		choice = sc.nextInt();
		if (choice <= 5){
			for (int i=0; i < choice; i++) {
			
				System.out.println("Enter the name of books you want to borrow ");
				books = sc.next(); 									//Students enter the book that they wanted to borrow
				
				System.out.println("Please enter the date of issuing following date of return.");
				System.out.println("Date of issuing:");
				date_1 = sc.next();									//Students enter the date of issuing
				
				System.out.println("Date of return:");
				date_2= sc.next();									//Students enter the date of return
				
				totalbooks = totalbooks - 1;						//Total books updated 
				}
				
			}
		else {
			System.out.println("The number of books that you want to borrow exceeds the maximum books that can be borrowed.");
			System.out.println("Please restart the program to borrow books from the library");
			System.exit(0);
		}
	
		System.out.println("============================================================================================================================== ");
		
		System.out.println("Fine will be given if students return the books past date of return "); //System explain on how the fined implemented
		System.out.println("The amount of fix fined is RM "+fine+".00");
		
		System.out.println("");
		fine1 = fine*1;
		fine2 = fine*2;
		fine3 = fine*4;
		fine4 = fine*4;
		fine5 = fine*5;
		
		
		
		System.out.println("                Days after date of return           Fine                 Total to be paid ");
		System.out.println("                        1                           RM"+fine+" X 1              RM"+fine1+".00           ");
		System.out.println("                        2                           RM"+fine+" X 1              RM"+fine2+".00           ");
		System.out.println("                        3                           RM"+fine+" X 1              RM"+fine3+".00           ");
		System.out.println("                        4                           RM"+fine+" X 1              RM"+fine4+".00           ");
		System.out.println("                        5                           RM"+fine+" X 1              RM"+fine5+".00           ");
		
		System.out.println(" ");
		
		System.out.println("After 5 days past the date of return, students will be reprimanded and blacklist for borrowing books from the library");
	
		System.out.println(" ");
		
		
		System.out.println("============================================================================================================================== ");
		
		
		System.out.println(" ");
		
		System.out.println("Thank you for using the University Library Management Sytsem ");
		System.out.println("There are  "+ totalbooks+ " books remaining in the library");
		System.out.println("Have a nice day! ");
		

	}

}
