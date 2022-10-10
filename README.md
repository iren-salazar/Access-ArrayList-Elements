# Access-ArrayList-Elements
simply names and foods to select with using ArrayList[elements]

package personal;

import java.util.ArrayList;

public class JavaUtilArrayList {
	public static void main(String[] args) {
		
		//create ArrayList
		ArrayList <String> names = new ArrayList <>();
		ArrayList <String> foods = new ArrayList <>();
		
		//ArrayList
		names.add("Elliot");
		names.add("Emmanuel");
		names.add("Cordelia");
		names.add("Kamaji");
		
		foods.add("Pizza");
		foods.add("Pineapple");
		foods.add("Calderita");
		foods.add("Adobong manok");
		
		//Store elements in ArrayList
		String favefood = foods.get(3);
		String character = names.get(3);
		//print ArrayList
		System.out.println("Come here " + character + " let's eat " + favefood + "!");
	}
}



