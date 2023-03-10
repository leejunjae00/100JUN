
package ex2_while;


import java.util.Random;

public class Ex1_while {
	public static void main(String[] args) {


//		int num = 1; 
//		
//		while(num <= 10) {
//			System.out.println(num);
//			num++;
//		}

//		Scanner scan = new Scanner(System.in);
//		
//		System.out.print("������ �Է����ּ���(-1�Է½� ����) : ");
//		int number = scan.nextInt();
//		
//		while(number != -1) {
//			System.out.println("�Է��Ͻ� ���ڴ� "+number + "�Դϴ�.");
//			
//			System.out.print("������ �Է����ּ���(-1�Է½� ����) : ");
//			number = scan.nextInt();
//		}



//		int i = 11;
//		
//		do {
//			System.out.println(i);
//		}while(i<=10);



		int java = 0, jsp = 0, android = 0;

		Random rnd = new Random();

		do {
			java = rnd.nextInt(131);
			jsp = rnd.nextInt(131);
			android = rnd.nextInt(131);			
		}while(java > 100 || jsp > 100 || android > 100);

		System.out.println("�ڹ� : " + java);
		System.out.println("JSP : " + jsp);
		System.out.println("�ȵ���̵� : " + android);











	}

}
