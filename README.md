# A006-T001
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int b = (int) n * (n + 1) / 2;
        int d = 0;

        for (int i = 0; i < n - 1; i++) {
            d += sc.nextInt();
        }
        System.out.println(b - d);
    }
}
