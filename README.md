# yousef

        import java.util.Locale;
        import java.util.Scanner;

        public class Main {
        public static void main(String[] args) {
        System.out.println("the first Question");
        /*1.	Develop a program that takes the weight (in kilograms) and height (in meters)
        as input and calculates the BMI, then prints it.*/
        Scanner s =new Scanner(System.in);
        System.out.println("please enter the weight");
        double weight =s.nextDouble();
        System.out.println("please enter the length");
        double length = s.nextDouble();
        length =length/100;
        double Mass = weight/(length*length);
        System.out.println(" Mass index "+Mass);

        /*2.	Write a program that takes the obtained marks and total marks
         as input and calculates the percentage, then prints it*/
        System.out.println("the second Question");
        System.out.println("please enter the degree");
        double degree =s.nextDouble();
        System.out.println("please enter the total marks");
        double total_Marks =s.nextDouble();
        double new_marks = (degree/total_Marks)*100;
        System.out.println("The last degree " + new_marks+"%");
        
        System.out.println("the third Question");
        /*3.	Create a program that takes an amount in one currency and an exchange rate as input,
        then converts and prints the amount in another currency*/
        System.out.println("please enter USD");
        double USD =s.nextDouble();
        USD =(USD/100)*85;
        System.out.println("the EUR= "+USD);

        /*4.	Create a program that takes a string as input, calculates its length, and then reverses the string using the StringBuilder class,
         finally printing both the length and reversed string.*/
        System.out.println("the fourth Question");

        String message = "Hello, World!";
       int count = message.length();
       String new_message= "";
       for (int i =count -1 ;i >=0 ;i--){
           new_message +=message.charAt(i);
       }
        System.out.println("length of message =" +count);
        System.out.println("new message: "+ new_message);
        ////////////////////////////////////////////////////
        /*5.	Develop a program that takes a sentence as input and extracts a substring from it,
         then prints the extracted substring.*/
        System.out.println("the Fifth Question");

        String inp ="The quick brown fox jumps over the lazy dog";
        System.out.println(inp.subSequence(10,20));
        /*6.	Write a program that takes a sentence and a keyword as input,
        then check if the keyword is present in the sentence and prints the result.*/
        System.out.println("the VI Question");

        System.out.println(inp.contains("jumps"));
        /*7.	Develop a program that takes a sentence and a word to replace as input,
        then replace all occurrences of the word with another word and prints the modified sentence.*/
        System.out.println("the  seven Question");
        System.out.println(inp.replace("fox" ,"cat"));
        /*8.	Write a program that takes two strings as input and check if they are equal, ignoring the case,
        then prints whether they are equal or not.*/
        System.out.println("the Eighth Question");

        String firstName = "yousef";

        System.out.println(firstName.equalsIgnoreCase("YOUSEF"));




    }
}
