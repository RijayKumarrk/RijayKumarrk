public class Reverse {

	public static void main(String[] args) {

		Scanner rk=new Scanner(System.in);

		System.out.println("enter array size");

		int size=rk.nextInt();

		int []b=new int[size];

		System.out.println("enter the array");

		for(int i=0;i<size;i++) {

			b[i]=rk.nextInt();

		}

		for(int i=0;i<size /2;i++) {

			int temp=b[i];

			b[i]=b[size - 1 - i];

			b[size - 1 - i]=temp;

			System.out.println("reversed array:");

			for(int num :b) {

			System.out.println( num );

			}

			

			

			

			

			

		}
