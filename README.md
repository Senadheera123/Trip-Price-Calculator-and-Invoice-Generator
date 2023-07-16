# DropMe™ Console Application
DropMe™ Console Application
This console application allows passengers to view trip details and generate invoices for the DropMe™ cab service.

**Prerequisites**
Python 3.x

**Installation**
Clone or download this repository.
Open a terminal or command prompt.
Navigate to the project directory.
Run the following command to install the required dependencies:

'pip install -r requirements.txt'

**Usage**
Open a terminal or command prompt.
Navigate to the project directory.
Run the following command to start the application:

'python dropme.py'

Enter the required information when prompted:

Location: Alvin, Jamz, Razi, Mali, or Zuhar.
Destination: Alvin, Jamz, Razi, Mali, or Zuhar.
Transport Choice: Trishaw, Car, or Van.
The application will calculate the trip price and generate an invoice file.

The generated invoice file will be saved in the current directory with the format "Invoice_YYYY-MM-DD_HH-MM-SS.txt".

Additional Features
Promo Codes: You can apply promo codes to deduct amounts from the final bill. Available promo codes include "pro2", "pro5", "pro10", and more.
Auto-generated Promotions: The application randomly generates promotions at a fixed price of 5 KMD for lucky passengers.
Price Chart
The price chart for the destinations is as follows:

City	Alvin	Jamz	Razi	Mali	Zuhar
Alvin	0	20	40	40	20
Jamz	20	0	20	40	40
Razi	40	20	0	20	40
Mali	40	40	20	0	20
Zuhar	20	40	40	20	0
For more information and command usage, refer to the comments in the dropme.py file.

