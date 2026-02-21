# Day-10.
Map
1. *Map is an interface that stores elements in key-value pairs.Other collections (List, Set) store only single elements.
   *It is the part of Java collection framework but it does not extend the collection interface.
   *Map does not allow duplicate keys.
   *We can get value directly using the key.

Example:
---------
public class MapExample {
    public static void main(String[] args) {
      Map<Integer, String> map = new HashMap<>();
        map.put(1, "Vinitha");
        map.put(2, "Venkadesh");
        System.out.println(map.get(1));
    }
}

2.Manual Testing:
  ---------------
Manual testing means testing the software manually without using automation tools.
When to use Manual Testing:
   *When the project is small.
   *When requirements change frequently.
   *For exploratory testing.
   *For UI and usability testing.
   *When test cases are executed only once or few times.

Automation Testing:
--------------------
Automation testing means testing the software using tools like Selenium.
When to use Automation Testing:
   *When test cases are repetitive.
   *For regression testing.
   *When the project is large.
   *When frequent builds are released.
   *To save time and increase accuracy.

Example Scenario:
-----------------
If a login page needs to be tested:
   Testing once → Manual testing is enough.
   Testing the login page every time after new update → Automation testing is better.

