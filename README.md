# pattern10

import java.util.Scanner;
public class Pattern9 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
        
		for(int i=1;i<=n;i++) {
			for(int j=1;j<=i;j++) {
				if(i%2==0) {
					System.out.print((char)(i+96));
				}
				else {
					System.out.print(i);
				}
			}
			System.out.println();
		}
	}
}

output ::                        ////when n is 5
5
1
bb
333
dddd
55555
