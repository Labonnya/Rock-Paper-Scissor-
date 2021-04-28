package string;
import java.util.Random; 
import java.util.Scanner;
public class RockPaperScissor {
    public static void main(String[] args) {
        for( ; ; ){
        int x=0,y=0,i;
        for(i=0;i<5;i++){
        Random rand = new Random();
        int upperbound = 3; 
        int random = rand.nextInt(upperbound);
        
        System.out.print("Enter rock, paper or scissor : ");
        Scanner input = new Scanner(System.in);
        String a = input.nextLine();
        if(random==0)
        {
            System.out.println("Computer has chosen Rock.");
        }
        else if(random==1)
        {
            System.out.println("Computer has chosen Paper.");
        }
        if(random==2)
        {
            System.out.println("Computer has chosen Scissor.");
        }
        if("rock".equalsIgnoreCase(a) && random==0){
            System.out.println("The game is tie.");
        } 
        else if("rock".equalsIgnoreCase(a) && random == 1)
        {
            System.out.println("You have lost.");
            x++;
        }
        else if("rock".equalsIgnoreCase(a) && random==2)
        {
            System.out.println("You have won.");
            y++;
        }
        else if("paper".equalsIgnoreCase(a) && random==1){
            System.out.println("The game is tie.");
        } 
        else if("paper".equalsIgnoreCase(a) && random == 0)
        {
            System.out.println("You have won.");
            y++;
        }
        else if("paper".equalsIgnoreCase(a) && random == 2)
        {
            System.out.println("You have lost.");
            x++;
        }
        else if("scissor".equalsIgnoreCase(a) && random == 1)
        {
            System.out.println("You have won.");
            y++;
        }
        else if("scissor".equalsIgnoreCase(a) && random == 0)
        {
            System.out.println("You have lost.");
            x++;
        }
        else if("scissor".equalsIgnoreCase(a) && random == 2)
        {
            System.out.println("The game is tie.");
        }
    }
        System.out.println("Final result: ");
        System.out.printf("Your point is %d.",y);
        System.out.printf("Computer's point is %d.",x);
        if(x>y)
        {
            System.out.println("\nCOMPUTER WON THE GAME.");
        }
        else if (y>x)
        {
            System.out.println("\nYOU WON THE GAME.");
        }
        else
        {
            System.out.println("\nThe game is a tie.");
        }
        System.out.println("Do you want to play again? ");
        Scanner input = new Scanner(System.in);
        String choice = input.nextLine(); 
       if("yes".equalsIgnoreCase(choice)) {
           continue;
        } else if("no".equalsIgnoreCase(choice))
       {
           break;
       }
}
}
}
