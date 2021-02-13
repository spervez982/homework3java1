# homework3part2.2

import java.util.Scanner; // Import the Scanner class

public class Java2 {

    private static void winnerCheck () {
        Scanner keyboard = new Scanner (System.in);
        System.out.println("enter the first number");
        int answer = keyboard.nextInt();
        System.out.println("enter the second number");
        int answer2 = keyboard.nextInt();
        System.out.println("enter the third number");
        int answer3 = keyboard.nextInt ();
        int winner=0;
        if (answer2<answer){
            winner=answer;
        }
        else winner=answer2;

        if (answer3>winner){
            winner=answer3;
        }
        else winner=winner;
        System.out.println(winner);
    }

    public static void main(String[] args) { 
      winnerCheck();
    }
}

 
