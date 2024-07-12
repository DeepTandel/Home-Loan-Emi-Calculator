# Home-Loan-Emi-Calculator
First Mini Project

Home Loan EMI Calculator Overview This project is a Java-based Home Loan EMI (Equated Monthly Installment) Calculator application with a graphical user interface (GUI). It allows users to calculate monthly EMI payments and generate a detailed amortization schedule, which can be exported to a PDF file.

Features : Loan Amount Slider: Adjust the loan amount between ₹1 Lac and ₹10 Crore. Tenure Slider: Set the tenure of the loan from 1 year to 30 years. Interest Rate Slider: Adjust the interest rate from 0% to 15%. EMI Calculation: Calculate the EMI based on the input parameters. Amortization Schedule: View the detailed amortization schedule in a table format. PDF Export: Export the amortization schedule to a PDF file. Getting Started

Prerequisites : Java Development Kit (JDK): Ensure you have JDK 8 or later installed on your system. iText Library: This project uses the iText library for PDF generation. You will need to include the iText JAR file in your project's classpath. Setting Up iText Library Download iText JAR: Download the iText library JAR file from the official iText website or from a trusted repository. Add JAR to Project: Using IDE (e.g., NetBeans, Eclipse)

1. NetBeans: -Right-click on your project and select "Properties." -Go to "Libraries" and click "Add JAR/Folder." -Navigate to the location of the downloaded iText JAR file and add it.

2. Eclipse: -Right-click on your project and select "Properties." Go to "Java Build Path" and select the "Libraries" tab. -Click "Add External JARs" and select the iText JAR file. -Manually: Place the iText JAR file in the lib directory of your project (create one if it doesn’t exist). -Ensure that the JAR file is included in the classpath when compiling and running the project.

Running the Project Compile and Run: Compile and run the project using your IDE or command line. Interacting with the GUI: Use the sliders to set the loan amount, tenure, and interest rate. Click the "OK" button to calculate and display the EMI and total amount payable. Click the "Print" button to export the amortization schedule to a PDF file. Code Overview Loan.java: The main class containing the GUI and the logic for EMI calculation and PDF generation. initComponents(): Initializes the GUI components and their layout. jButton1ActionPerformed(): Calculates the EMI and updates the amortization table. jButton2ActionPerformed(): Exports the amortization table to a PDF file using iText.

Contribution Feel free to fork the repository and submit pull requests. Contributions are welcome!

Contact For any questions or issues, please contact deeptandel1405@gmail.com
