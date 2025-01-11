# Switch-case
Public class Switch Case Demo {

Public static void main(String[] args){

Scanner Sc = new Scanner(System.in);

System.out.println("Enter a number (1-7) to display the corresponding day of

the week: ");

int day = sc.nextInt();

Switch (day) {

Case 1:

System.out.println("Monday");

case 2:

System.out.println("Tuesday");

case 3:

System.out.println("Wednesday");

case 4:

System.out.println("Thursday");

case 5:

System.out.println("Friday");

Case 6:

System.out.println(" Saturday");

case 7:

System.out.println(“sunday");

default:

System.out.println("Invalid input

Please enter a number between 1
and 7. "); 

}

Scanner. cloce();

}

}

Output

Enter a number (1-7) to display the Corresponding day of the week:

3

Wednesday

Enter a number (1-7) to display the Corresponding day of the week:

9

Invalid input please enter a number between I and 7.
