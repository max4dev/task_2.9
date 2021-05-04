# task_2.9

public class Main {

    public static void main(String[] args) {

        int numbers [] = {2, 3, 4, 8, 5};
        int counter = 0;


        for (int i = 0; i < numbers.length; i++) {
            if (numbers[i] == 5) {
                System.out.println("Да");
                counter ++;
            }
            if (i == numbers.length-1 && counter == 0) {
                System.out.println("Нет");
            }
        }
    }
}
