# C016:Leet文字列
Paiza C rank

import java.util.*;


public class Main {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        String s = sc.next();//変換する前の値
        int len = s.length();
        if(1 <= len && len <= 100){ //入力は1～100まで
            //if(checkHoge(s) == true){
                 s= s.replace("A","4");
                 s= s.replace("E","3");
                 s= s.replace("G","6");
                 s= s.replace("I","1");
                 s= s.replace("O","0");
                 s= s.replace("S","5");
                 s= s.replace("Z","2");
                
                System.out.println(s);
            //}
        }
    }
}
