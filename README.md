# IBM-Project-15534-1659600186
Smart Solutions For Railways


TEAM LEADER
Golla Vinay Kumar

TEAM MEMBERS
Vadlamudi SaiGuruKrishna
Kalamakuntla Bhavani
Theetla Raj VarunKumar

OBJECTIVE:
* Gain knowledge of Watson IoT Platform.
* Connecting IoT devices to the Watson IoT platform and exchanging the sensor data.
* Gain knowledge on IBM Cloudant DB
* Explore Python client libraries of Watson IoT Platform.
* Explore Python library for integrating OpenCV for accessing the Live Camera Input
* Scan the QR code in live streaming and retrieve the QR code details
* Gain knowledge on web application development.
* Gain knowledge of storing the data in Cloudant DB
* Generating QR codes with the required data.
PROJECT FLOW:
* Using the Web application, a user books a ticket based on the availability of the seats by giving the general required information.
* Once a user clicks on the submit button, a QR code is generated with a Unique ID and the data is stored in the Cloudant DB with that Unique ID.
* Users can save the QR code for further process.
* In python code, a Ticket collector can scan the QR code and extract the information from the QR Code i.e., Unique ID. With that Unique ID, data is fetched from the       Cloudant DB, if it is not found, then it displays Not a Valid Ticket.
* Also, the live location of the train will be published to IBM IoT platform using python code
* The train location can be tracked from a Web Application
