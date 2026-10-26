import java.lang.*;
import java.util.*;

public class Main {
    public static void main(String[] args) {
        // YOUR CODE GOES HERE
        // Please take input and print output to standard input/output (stdin/stdout)
        // DO NOT USE ARGUMENTS FOR INPUTS
        // E.g. 'Scanner' for input & 'System.out' for output
        for(int i=0;i<=6;i++)
        {
            if(i==0||i==3||i==6)
            {
                for(int j=0;j<6;j++)
                {
                    System.out.print("*");

                }
            }
            else if(i==1||i==2)
                {
                    for(int j=0;j<1;j++)
                    {
                        System.out.print("*");
                    }
                }
                else
                {
                    if(i==4||i==5)
                    {
                        for(int j=0;j<6;j++)
                        {
                            if(j==5)
                            {
                                System.out.print("*");
                            }
                            else{
                                System.out.print(" ");
                            }
                        }
                    }



                }
            

            
            System.out.println();
        }
        
    }
}
