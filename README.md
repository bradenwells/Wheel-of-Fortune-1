# Wheel-of-Fortune-1public static void main(String[] args) {
        // TODO code application logic here
         System.out.println("Welcome to Wheel of Fortune!");
        //Brtaden Wells Original wheel of fortune
        int fk = 0;
        while(fk == 0)
        {
    System.out.println("To play a standard game enter S. To play a chirstmas version press C.");
    System.out.println("To exit enter E.");
    String startMain = scMain.next();
    switch (startMain) case "s":
        {
                 
        
  before_and_after [0] = "A Blast From The Past Present And Future";
  before_and_after [1] = "A Chip Off Of The Old Block Party";
  before_and_after [2] = "A Hole In One Way Ticket";
  before_and_after [3] = "A House Is Not A Home On The Range";       
  before_and_after [4] = "A Long Shot In The Dark";
        
                        
        
  on_the_map [0] = "The North Pole";
  on_the_map [1] = "Rockefeller Center New York";
  on_the_map [2] = "Santa Claus Georgia";
  on_the_map [3] = "Christmasville Tennessee";
  on_the_map [4] = "Mistletoe Kentucky";
        
  what_are_you_doing [0] = "Trimming The Tree";
  what_are_you_doing [1] = "Wrapping The Presents";
  what_are_you_doing [2] = "Attending Church Service";
  what_are_you_doing [3] = "Spending Time With Family";
  what_are_you_doing [4] = "Hanging Mistletoe";
                        fk++;
    break;
 
   case "e": System.out.println("Goodbye!");//need to close program when e is chosen
                          fk++;
     System.exit(0);//Exits the program
                break;
        default: System.out.println("Not a valid choice");
                break;
            }
        }
