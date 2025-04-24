# Advance-Programming-Assignment-No-4
Assignment no 4 (Hash Maping)

java code 

import java.util.HashMap;

public class HashMapSearchExample {
    public static void main(String[] args) {
        HashMap<String, String> favoriteColors = new HashMap<>();

        favoriteColors.put("Alice", "Blue");
        favoriteColors.put("Bob", "Green");
        favoriteColors.put("Charlie", "Red");

        String nameToSearch = "Bob";

        if (favoriteColors.containsKey(nameToSearch)) {
            String color = favoriteColors.get(nameToSearch);
            System.out.println(nameToSearch + "'s favorite color is: " + color);
        } else {
            System.out.println(nameToSearch + " was not found in the list.");
        }
    }
}

