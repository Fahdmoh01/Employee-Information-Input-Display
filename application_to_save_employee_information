import java.util.Scanner;
public class Project1 {
	public static void main(String args[]){
	String emp[][]={
	{"Emp No."," Emp Name"," Join Date"," Desig Code"," Department"," Basic"," HRA"," IT"},
	{"1001","Ashish","01/04/2009","e","R&D","20000","8000","3000"},
	{"1002","Sushma","23/08/2012","c","PM","30000","12000","9000"},
	{"1003","Rahul","12/11/2008","k","Acct","10000","8000","1000"},
	{"1004","Chahat","29/01/2013","r","Front Desk","12000","6000","2000"},
	{"1005","Ranjan","16/07/2005","m","Engg","50000","20000","20000"},
	{"1006","Suman","01/01/2000","e","Manufacturing","23000","9000","4400"},
	{"1007","Tanmay","12/06/2006","c","PM","29000","12000","10000"}
	};

	String desig[][]={{"Designation Code", "Designation", "DA"},
	 {"e","Engineer","20000"},
	 {"c","Consulant","32000"},
	 {"k","Clerk","12000"},
	 {"r","Recptionist","15000"},
	 {"m","Manager","40000"}
	};
	int emp_no; 
	Scanner scan = new Scanner(System.in);
	System.out.println("Enter Employee Number to display employee information");
	Scanner sc=new Scanner(System.in);
	emp_no=sc.nextInt();
	int salary=0; 
	switch(emp_no)
	{
	 case 1001:
	  System.out.println(emp[0][0]+" "+emp[0][1]+" "+emp[0][2]+" "+emp[0][4]+" "+desig[0][1]+" "+ "Salary");
	  salary+=Integer.parseInt(emp[1][5])+Integer.parseInt(emp[1][6])+Integer.parseInt(desig[1][2]) - Integer.parseInt(emp[1][7]);
		System.out.println(emp[1][0]+"     "+emp[1][1]+"    "+emp[1][2]+"    "+emp[1][4]+"      "+desig[1][1]+"   "+salary); 
	  break;
	 case 1002:
		 System.out.println(emp[0][0]+" "+emp[0][1]+" "+emp[0][2]+" "+emp[0][4]+" "+desig[0][1]+" "+ "Salary");
		  salary+=Integer.parseInt(emp[2][5])+Integer.parseInt(emp[2][6])+Integer.parseInt(desig[2][2]) - Integer.parseInt(emp[2][7]);
			System.out.println(emp[2][0]+"     "+emp[2][1]+"    "+emp[2][2]+"    "+emp[2][4]+"      "+desig[2][1]+"   "+salary); 
		  break;
	 case 1003:
		 System.out.println(emp[0][0]+" "+emp[0][1]+" "+emp[0][2]+" "+emp[0][4]+" "+desig[0][1]+" "+ "Salary");
		  salary+=Integer.parseInt(emp[3][5])+Integer.parseInt(emp[3][6])+Integer.parseInt(desig[3][2]) - Integer.parseInt(emp[3][7]);
			System.out.println(emp[3][0]+"      "+emp[3][1]+"    "+emp[3][2]+"    "+emp[3][4]+"       "+desig[3][1]+"    "+salary); 
		  
		 break;
	 case 1004:
		 System.out.println(emp[0][0]+" "+emp[0][1]+" "+emp[0][2]+" "+emp[0][4]+" "+desig[0][1]+" "+ "Salary");
		  salary+=Integer.parseInt(emp[4][5])+Integer.parseInt(emp[4][6])+Integer.parseInt(desig[4][2]) - Integer.parseInt(emp[4][7]);
			System.out.println(emp[4][0]+"     "+emp[4][1]+"    "+emp[4][2]+"    "+emp[4][4]+"      "+desig[4][1]+"   "+salary); 
		  
		 break;
	 case 1005:
		 System.out.println(emp[0][0]+" "+emp[0][1]+" "+emp[0][2]+" "+emp[0][4]+" "+desig[0][1]+" "+ "Salary");
		  salary+=Integer.parseInt(emp[5][5])+Integer.parseInt(emp[5][6])+Integer.parseInt(desig[5][2]) - Integer.parseInt(emp[5][7]);
			System.out.println(emp[5][0]+"     "+emp[5][1]+"    "+emp[5][2]+"    "+emp[5][4]+"      "+desig[5][1]+"   "+salary); 
		  
		 break;
	 case 1006:
		 System.out.println(emp[0][0]+" "+emp[0][1]+" "+emp[0][2]+" "+emp[0][4]+" "+desig[0][1]+" "+ "Salary");
		  salary+=Integer.parseInt(emp[6][5])+Integer.parseInt(emp[6][6])+Integer.parseInt(desig[6][2]) - Integer.parseInt(emp[6][7]);
			System.out.println(emp[6][0]+"     "+emp[6][1]+"    "+emp[6][2]+"    "+emp[6][4]+"      "+desig[6][1]+"   "+salary); 
		  
		 break;
	 case 1007:
		 System.out.println(emp[0][0]+" "+emp[0][1]+" "+emp[0][2]+" "+emp[0][4]+" "+desig[0][1]+" "+ "Salary");
		  salary+=Integer.parseInt(emp[7][5])+Integer.parseInt(emp[7][6])+Integer.parseInt(desig[7][2]) - Integer.parseInt(emp[7][7]);
			System.out.println(emp[7][0]+"     "+emp[7][1]+"    "+emp[7][2]+"    "+emp[7][4]+"      "+desig[7][1]+"   "+salary); 
		  
		 break;
	 default: 
		 System.out.println("There is no employee with empid:" + emp_no );
		 break;
	}	 

}
	}
