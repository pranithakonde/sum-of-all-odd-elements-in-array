# sum-of-all-odd-elements-in-array
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s = new Scanner(System.in);
        int N = s.nextInt();
        int a[] = new int[N];
        int sum=0;
        for(int i=0;i<N;i++)
        {
             a[i] = s.nextInt();
        }
        for(int i=0;i<N;i++)
        {
            if(a[i]%2!=0)
                sum+=a[i];
        }
        System.out.println(sum);
    }
}
