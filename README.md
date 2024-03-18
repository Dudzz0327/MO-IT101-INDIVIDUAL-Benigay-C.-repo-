

public class Employee {
	
}
public class main {
	public static String[] employee_hourly_rate;
	public static String[] employee;
	public static String[] Position;
	public static String[] Basic_salary;
	
	

	

	public static void main(String [] args) {
		
		boolean conts = true;
		while (conts) {
			System.out.println("======= Start of Session ===========");
			define_data_type();
//			System.out.println("hourly rate : "+employee_hourly_rate);
//			System.out.println(Arrays.toString(employee));

			
			// return 0 if empty
			// return n if it's working
			if(employee.length != 0) {
				employee[0] = "Not Registered";
				System.out.println("Employee ID: " + employee[0]);
				//employee details
				employee[1] = "Manuel Garcia III";
				employee_hourly_rate[1] = "535.71";
				Basic_salary[1] = "90,000"; 
				Position[1] = "Chief Operation Office";
				
				employee[2] = "Antonio Lim";
				employee_hourly_rate[2] = "357.71";
				Basic_salary[2] = "60,000";
				Position[2] = "Chief Operating Oficcer";
				
				employee[3] = "Bianca Sofia Aquino";
				employee_hourly_rate[3] = "357.14";
				Basic_salary[3] = "60,000";
				Position[3] = "Chief Finance Officer";
				
				employee[4] = "Isabella Reyes";
				employee_hourly_rate[4] = "357.14";
				Basic_salary[4] = "60,000";
				Position[4] = "Chief Marketing Officer";
						
				employee[5] = "Eduard Hernandez";
				employee_hourly_rate[5] = "313.51";
				Basic_salary[5] = "52,670";
				Position[5] = "IT Operations and Systems";
						
				employee[6] = "Andrea Mae Villanueva";
				employee_hourly_rate[6] = "313.51";
				Basic_salary[6] = "52,670";
				Position[6] = "HR Manager";
				
				employee[7] = "Brad Sam Jose";
				employee_hourly_rate[7] = "255.80";
				Basic_salary[7] = "42,970";
				Position[7] = "HR Team Leader";
				
				employee[8] = "Alice Romualdez";
				employee_hourly_rate[8] = "133.93";
				Basic_salary[8] = "22,500";
				Position[8] = "HR Rank and File";
						
				employee[9] = "Rosie Atienza";
				employee_hourly_rate[9] = "133.93";
				Basic_salary[9] = "22,500";
				Position[9] = "HR Rank and File";
						
				employee[10] = "Roderick Alvaro";
				employee_hourly_rate[10] = "313.51";
				Basic_salary[10] = "52,670";
				Position[10] = "HR Rank and File";
				
				employee[11] = "Anthony Salcedo";
				employee_hourly_rate[11] = "302.53";
				Basic_salary[11] = "50,825";
				Position[11] = "Accounting Head";
				
				employee[12] = "Josie Lopez";
				employee_hourly_rate[12] = "229.02";
				Basic_salary[12] = "38,475";
				Position[12] = "Payroll Team Leader";
				
				employee[13] = "Martha Farala";
				employee_hourly_rate[13] = "142.86";
				Basic_salary[13] = "24,000";
				Position[13] = "Payroll Rank and File";
				
				employee[14] = "Leila Martinez";
				employee_hourly_rate[14] = "142.86";
				Basic_salary[14] = "24,000";
				Position[14] = "Payroll Rank and File";
				
				employee[15] = "Fredrick Romualdez";
				employee_hourly_rate[15] = "318.45";
				Basic_salary[15] = "53,500";
				Position[15] = "Account Manager";
						
				employee[16] = "Christian Mata";
				employee_hourly_rate[16] = "255.80";
				Basic_salary[16] = "42,975";
				Position[16] = "Account Team Leader";
				
				employee[17] = "Selena De Leon";
				employee_hourly_rate[17] = "249.11";
				Basic_salary[17] = "41,850";
				Position[17] = "Account Team Leader";
				
				employee[18] = "Allison San Jose";
				employee_hourly_rate[18] = "133.93";
				Basic_salary[18] = "22,500";
				Position[18] = "Account Rank and File";
				
				employee[19] = "Cydney Rosario";
				employee_hourly_rate[19] = "133.93";
				Basic_salary[19] = "22,500";
				Position[19] = "Account Rank and File";
				
				employee[20] = "Mark Baustista";
				employee_hourly_rate[20]= "138.39";
				Basic_salary[20] = "23,250";
			    Position[20] = "Account Rank and File";
			    
				employee[21] = "Darlene Lazaro";
				employee_hourly_rate[20] = "138.39";
				Basic_salary[20] = "23,250";
				Position[20] = "Account Rank and File";
				
				employee[22] = "Kolby Delos Santos";
				employee_hourly_rate[22] = "142.86";
				Basic_salary[22] = "24,000";
				Position[22] = "Account Rank and File";
				
				employee[23] = "Vella Santos";
				employee_hourly_rate[23] = "133.93";
				Basic_salary[23] = "22,500";
				Position[23] = "Account Rank and File";
				
				employee[24] = "Tomas Del Rosario";
				employee_hourly_rate[24] = "133.93";
				Basic_salary[24] = "22,500";
				Position[24] = "Account Rank and File";
				
				employee[25] = "Jacklyn Tolentino";
				employee_hourly_rate[25] = "142.86";
				Basic_salary[25] = "24,000";
				Position[25] = "Account Rank and File";
				
				employee[26] = "Percival Gutierrez";
				employee_hourly_rate[26] = "147.32";
				Basic_salary[26] = "24,750";
				Position[26] = "Account Rank and File";
				
				employee[27] = "Garfield Manalaysay";
				employee_hourly_rate[27] = "147.32";
				Basic_salary[27] = "24.750";
				Position[27] = "Account Rank and File";
				
				employee[28] = "Lizeth Villegas";
				employee_hourly_rate[28] = "142.86";
				Basic_salary[28] = "24,000";
				Position[28] = "Account Rank and File";
				
				employee[29] = "Carol Ramos";
				employee_hourly_rate[29] = "133.93";
				Basic_salary[29] = "22,500";
				Position[29] = "Account Rank and File";
				
				employee[30] = "Emelia Maceda";
				employee_hourly_rate[30] = "133.93";
				Basic_salary[30] = "22,500";
				Position[30] = "Account Rank and File";
				
				employee[31] = "Delia Aguilar";
				employee_hourly_rate[31] = "133.93";
				Basic_salary[31] = "22,500";
				Position[31] = "Account Rank and File";
				
				employee[32] = "John Rafael Castro";
				employee_hourly_rate[32] = "313.51";
				Basic_salary[32] = "52,670";
				Position[32] = "Sales & Marketing";
				
				employee[33] = "Carlos Ian Martinez";
				employee_hourly_rate[33] = "313.51";
				Basic_salary[33] = "52,670";
				Position[33] = "Supply Chain and Logisctics";
				
				employee[34] = "Beatriz Santos";
				employee_hourly_rate[34] = "313.51";
				Basic_salary[34] = "52,670";
				Position[34] = "Custome Service and Relation";
				
				System.out.println("Name: " + employee[1] + ", " + employee[2]);
				System.out.println("Position: " + employee[11]);
				System.out.println("hourly salary: " + employee[18]);
				System.out.println("Basic Salary: " + sanitize_data(employee[13]));
				
				System.out.println("============== Calculation ==============");
				String sss_contrib = get_sss_calculation();
				
			} else {
				System.out.println("No data found. Please try again");
			}
			System.out.println("======= End of Session ===========");
			System.out.println("**********************************");
		}
	}
	
	public static void reset_data() {
		employee_hourly_rate[1]= "";
		employee = new String [0];
	}
	
	public static void define_data_type() {
		reset_data();
		System.out.print("Enter an Employee number: ");
		
		BufferedReader inputReader = new BufferedReader(new InputStreamReader(System.in));
		try {
			String userInput = inputReader.readLine();
			
			String employee_detail = get_employee_details(userInput);
			
			if(!employee_detail.equals("")) {
				String[] row = employee_detail.split(",");
				employee = row;
				employee_hourly_rate = row[18];
			}
		} catch (IOException e) {
			e.printStackTrace();
		}

		

	}
	
	public static String sanitize_data(String info) {
		return info.replace(";x;", ",").replace("\"", "");
	}
	
	public static String get_employee_details(String employee_id) {
		// identify the file directory
		String file = System.getProperty("user.dir") + "/src/employee_details.csv";
		
		// initialize the variables
		BufferedReader reader = null;
		String line = "";
		String employee_found = "";
		
		try {
			// get the csv file from directory and load it onto your java project
			reader = new BufferedReader(new FileReader(file));
			
			// tell the system to iterate on each line of the csv
			while ((line = reader.readLine()) != null) {
				
				String repl = line.replaceAll(",(?!(([^\"]*\"){2})*[^\"]*$)", ";x;");
				String[] row = repl.split(",");

				if (Integer.parseInt(row[0]) == Integer.parseInt(employee_id)) {
					employee_found = repl;
				}

			}
		} catch (Exception e) {e.printStackTrace(); }
		
		return employee_found;
		
	}
	
	public static String get_sss_calculation() {
		
		String d_montly_salary = employee[13].replace(";x;", "").replace("\"", "");
		System.out.println("monthly salary: "+d_montly_salary);
		return null;
		
		
	}
    
}	
