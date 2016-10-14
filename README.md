# assignment1

public class MessagePrinter{
	public static void main(String args[]){
		//store other class in variable
		Messages copyOfMessages = new Messages();
		// print name
		copyOfMessages.namePrinter();
		// print papa
		copyOfMessages.wordPrinter();
		// print (input+1) provided to paramater 
		copyOfMessages.incrementPrinter(5);
	}
}

/////////////////////////////////////////////////////////

public class Messages {

		//prints my name
		public static void namePrinter(){
			System.out.println("Leon");
		}
		//prints papa
		public static void wordPrinter(){
			System.out.println("Papa");
		}
		//prints input no. + 1
		public static void incrementPrinter(double number){  
		//may need to remove void if returning a value
		// probably take input in argument then add 1 to it.

		// number input	DO WE NEED TO DECLARE ABOUT BECAUSE ITS IN PARAMETER?
	
		// number input + 1
		double output = number+1;
		// print the (number input + 1), maybe return, im not sure 
			System.out.println(output);
		}
}
