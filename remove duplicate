import java.util.ArrayList;
import java.util.Scanner;

public class RemoveDuplicates {
    public static void main(String[] args) {
        ArrayList<Integer> list = new ArrayList<>();
        Scanner scanner = new Scanner(System.in);

//asking user to enter 10 digits 
        System.out.print("Enter ten integers: ");
        for (int i = 0; i < 10; i++) {
            int num = scanner.nextInt();
            list.add(num);
        }

        removeDuplicate(list);

//will read the numbers back without duplicats 
        System.out.print("The distinct integers are ");
        for (int num : list) {
            System.out.print(num + " ");
        }
    }

    public static void removeDuplicate(ArrayList<Integer> list) {
        ArrayList<Integer> distinctList = new ArrayList<>();
        for (int num : list) {
            if (!distinctList.contains(num)) {
                distinctList.add(num);
            }
        }
        list.clear();
        list.addAll(distinctList);
    }
}
