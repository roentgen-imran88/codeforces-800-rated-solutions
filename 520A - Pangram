# Solution to 520A - Pangram 


import java.util.*;

public class time{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        String s1 = sc.next();

        String s2 = s1.toLowerCase();
        String s3 = "abcdefghijklmnopqrstuvwxyz";



        char b[] = s2.toCharArray();
        char c[] = s3.toCharArray();

        Map<Character,Integer> map1 = new HashMap<>();
        Map<Character,Integer> map2 = new HashMap<>();


        for(char f : b)
        {
            if(map1.containsKey(f))
            {
                map1.put(f,map1.get(f)+1);
            }
            else
            {
                map1.put(f,1);
            }
        }

        for(char g : c)
        {
            if(map2.containsKey(g))
            {
                map2.put(g,map2.get(g)+1);
            }
            else
            {
                map2.put(g,1);
            }
        }

        if(map2.keySet().equals(map1.keySet()))
        {
            System.out.println("YES");
        }
        else
            System.out.println("NO");

    }

}
