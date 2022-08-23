import java.util.Scanner;  // This import the Scanner class from the Java library
public class DogTestDrive {// Start class
	
	// Make reference to the Scanner class using variables input
    static Scanner input = new Scanner(System.in);  // This create a Scanner object
    // Declare global variables which can be used throughout the program
    static int 
    Pass,
    Fail,
    Hgrade,
    Lgrade=101, 
    total=0;

    public static void main(String[] args) {// Start main
   
    	System.out.println(" ");
    	System.out.println("\t\t\t\t*********** Welcome to Eskandar's GRADEBOOK ***********\n");
    	
    	//Ask the user to enter the name of the course and class group 
    	System.out.println("Please enter the class name");
    	//Declare a variable for the name of the course and class group
    	String ClassName= input.nextLine();
    	// Ask the user how many students are in this group
    	System.out.println("How many students are in"+" "+ClassName+" ?");
    	// Declare a variable for the number of students from user input
    	int studentsNb= input.nextInt();
    	
    	for (int i=1; i<=studentsNb;i++){
    		// Ask user to enter each student's grade
    		System.out.println("Please enter the grade for student "+i+" :");
    		// Declare variable for the student's grade from user input
    		int studentGrade=input.nextInt();
    		// Calculating total grade
    	    total=total+studentGrade;
    		// if statement to determine which grade passes or fails
    		if (studentGrade>49){
    			Pass++;// Increment -> nbPassGrades=nbPassGrades+1	
    		}// End of if statement
    		else{// else statement 
    			Fail++; // Increment -> nbFailGrades=nbFailGrades+1
    		}// End of else statement
    		// if statement to determine the highest grade
    		if(studentGrade > Hgrade){
    			Hgrade = studentGrade;
    		}// End of if statement
    		// if statement to determine the lowest grade
    	    if (studentGrade< Lgrade){
    			Lgrade=studentGrade;
    		}// End if statement
    	}// End of the for loop
    	// Final print report
    	System.out.println(" ");
    	System.out.println("\t\t\t\t***** GRADEBOOK'S REPORT "+ClassName+" *****");
    	System.out.println(" ");
    	System.out.println("\t\t\t\t--------------------------------------------------");
    	System.out.println("\t\t\t\tThe number of passes is "+Pass);
     	System.out.println("\t\t\t\tThe number of fails is "+Fail);
     	System.out.println("\t\t\t\t--------------------------------------------------");
     	System.out.println("\t\t\t\tThe highest grade is "+Hgrade);
     	System.out.println("\t\t\t\tThe lowest grade is "+Lgrade);
     	System.out.println("\t\t\t\t--------------------------------------------------");
     	System.out.println("\t\t\t\t\t\t\t\t       Total: "+total);
     	System.out.println("\t\t\t\t\t\t\t\t       Average: "+(total/studentsNb));
   }// End main     
}// End class
