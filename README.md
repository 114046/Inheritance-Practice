
 * Your implementation of the SmartCat class.
 */

public class SmartCat [...] {

	//declare a variable to store the owner's name as a String 
	private String name;

	//create a construtor that takes in the cat name and owner's name
	public SmartCat(String catName, String name){
	   super(name, catName0);
	   
	}

	//override the speak method so that it returns the String "Hello [owner's name]"
	@Override
	public String speak(){
	   return "Hello " + name;
	}

	//override the toString method so that it returns the String: "Smart Cat: [cat's name]; Owner: [Owner's name]"
	@Override
	public String toString(){
	   System.out.print("Smart Cat: " + catName);
	   System.out.println("Owner: " + name);
	}
	

}
