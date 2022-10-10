# Access-ArrayList-Elements
simply birthday letter to select with using ArrayList -accessing the elements in ArrayList

package personal;

import java.util.ArrayList;

public class JavaUtilArrayList {
	public static void main(String[] args) {
		
		//create ArrayList
		ArrayList <String> names = new ArrayList <>();
		ArrayList <String> foods = new ArrayList <>();
		ArrayList <String> work = new ArrayList <>();
		
		//ArrayList
		names.add("Elliot");
		names.add("Cordelia");
		names.add("Kamaji");
		foods.add("Pizza");
		foods.add("Pineapple");
		foods.add("Adobong manok");
		work.add("Cook");
		work.add("Nutritionist");
		work.add("Pro Chief");

		
		//Store elements in ArrayList
		String favefood = foods.get(2);
		String character = names.get(2);
		String jobs = work.get(0);
		String sender = names.get(0);
		
		//print ArrayList
		System.out.println("\"Birthday Message\"");
		System.out.println("\rHello " + character + " happy birthday to you! " + 
		"\rThanks for the " + favefood + "!" + " It was so delicious..." + " You are always been a good " +
		jobs + "\rI wish you all the best in life can give and I hope to see you soon.\r" +
		"\rYour loyal friend,\r" + sender );
	}
}






