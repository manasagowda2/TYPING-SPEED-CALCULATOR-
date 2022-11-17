# TYPING-SPEED-CALCULATOR-
import java.time.LocalTime;
import java.util.Random;
import java.util.Scanner;
import java.util.concurrent.TimeUnit;
public class WPMProgram {
static String[] words = 
{"you","me","went","college","engineering","mother","india",
"computer science","coffee","love","universal"};
public static void main(String[] args) throws 
InterruptedException {
// TODO Auto-generated method stub
 System.out.println("3");
 TimeUnit.SECONDS.sleep(1);
 
 System.out.println("2");
 TimeUnit.SECONDS.sleep(1);
 
 System.out.println("1");
 TimeUnit.SECONDS.sleep(1);
 
 Random rand = new Random();
 for(int i=0; i<11; i++) {
 System.out.print(words[rand.nextInt(10)] + " ");
 }
 System.out.println();
 
 double start = LocalTime.now().toNanoOfDay();
 
 Scanner scan = new Scanner(System.in);
 String typedWords = scan.nextLine();
 double end = LocalTime.now().toN double elapsedTim
