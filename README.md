# AcessModifiersInJava
//Java Programming
public class New {
    public static void main(String[] args) 
    //object instantiation
    {
      MyEmployee Socks = new MyEmployee();
      // method call of getName and setName
      Socks.setName("ShivaniSharma");
        System.out.println(Socks.getName());
    }
}
//main class
class MyEmployee{
//implementing access modifiers
    private int id;
    private String name;
    //implementing getters and setters
    public String getName(){
        return name;
    }
        public void setId(int i){
            id =i;}

    public int getId(){
        return id;
    }
    public void setName(String n){
        name =n;
}
}
