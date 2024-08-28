play the superhero quiz! lets see if you can get them all right

```java
import java.util.Scanner;

public class SuperheroTrivia {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int score = 0;

        System.out.println("Welcome to the Superhero Trivia Quiz!");
        System.out.println("Answer the following questions to test your superhero knowledge.");
        System.out.println();

        // Question 1
        System.out.println("Question 1: What is Superman's birth name?");
        System.out.println("1. Kal-El");
        System.out.println("2. Clark Kent");
        System.out.println("3. Jor-El");
        System.out.println("4. Bruce Wayne");
        int answer1 = scanner.nextInt();
        if (answer1 == 1) {
            score++;
        }

        // Question 2
        System.out.println("Question 2: Who is known as the 'Scarlet Speedster'?");
        System.out.println("1. Superman");
        System.out.println("2. The Flash");
        System.out.println("3. Wonder Woman");
        System.out.println("4. Spider-Man");
        int answer2 = scanner.nextInt();
        if (answer2 == 2) {
            score++;
        }

        // Question 3
        System.out.println("Question 3: What is the name of Thor’s hammer?");
        System.out.println("1. Mjolnir");
        System.out.println("2. Stormbreaker");
        System.out.println("3. Gungnir");
        System.out.println("4. Excalibur");
        int answer3 = scanner.nextInt();
        if (answer3 == 1) {
            score++;
        }

        // Question 4
        System.out.println("Question 4: Which superhero is also known as the 'Caped Crusader'?");
        System.out.println("1. Iron Man");
        System.out.println("2. Batman");
        System.out.println("3. Captain America");
        System.out.println("4. Wolverine");
        int answer4 = scanner.nextInt();
        if (answer4 == 2) {
            score++;
        }

        // Question 5
        System.out.println("Question 5: What is the real name of the superhero Black Widow?");
        System.out.println("1. Natasha Romanoff");
        System.out.println("2. Wanda Maximoff");
        System.out.println("3. Carol Danvers");
        System.out.println("4. Peggy Carter");
        int answer5 = scanner.nextInt();
        if (answer5 == 1) {
            score++;
        }

        // Display final score
        System.out.println("\nYour final score is: " + score + " out of 5!");

        // Provide feedback based on score
        if (score == 5) {
            System.out.println("Amazing! You're a superhero expert!");
        } else if (score >= 3) {
            System.out.println("Great job! You know your superheroes.");
        } else {
            System.out.println("Nice try! Keep learning about superheroes.");
        }

        scanner.close();
    }
}
