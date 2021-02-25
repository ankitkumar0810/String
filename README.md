# String
Write a java program to read a name and print "Welcome" message

public class ReadName {

    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);
        
        String name;
        
        name = sc.nextLine();
        
        System.out.println("Welcome " + name);
    }
    
}
