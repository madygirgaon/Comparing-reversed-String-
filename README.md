# Comparing-reversed-String-
import java.util.*;
public class Main{
    public static void main(String[]args){
        Scanner scan=new Scanner(System.in);
        String str=scan.nextLine();
        String s="";
        char ch;
        ;
        for(int i=0;i<str.length();i++){
            ch=str.charAt(i);
            s=ch+s;
            
        }
        if(str.equals(s)){
        System.out.println("Yes");
    }
    else{
        System.out.println("No");
    }
    }
}
