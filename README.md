# pattern_code
package Startproject;

public class pattern {

	public static void main(String[] args) 
	{
		// TODO Auto-generated method stub
		int n = 7;
		
			
			for(int i=0 ;i<n; i++)
				{
				    for(int k=0 ; k < (n-1)-i ; k++)
						{
						  System.out.print(" ");
						} 
					
					for(int j = 0 ; j<=i ;j++)
						
					{
					    if(j==0 || i ==n-1 || j==i)
						{
							System.out.print("* ");
						}
						else
						{
							System.out.print("  ");	
						}
				
			
					}
			
						System.out.println();
				}
    }
	
}

