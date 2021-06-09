# prime
package fibannoci;
import java.util.*;
public class fabnocci {

	public static void main(String[] args) {
		int num;
		int c=0;
		Scanner sc=new Scanner(System.in);
		num=sc.nextInt();
			for(int i=2;i<num;i++){
				if(num%i==0){
					System.out.println(num+" is not prime number");
					c=1;
					break;
				
				}
			}
			if(c==0){
				System.out.println(num+" is a prime");
				
			}
			}
}


