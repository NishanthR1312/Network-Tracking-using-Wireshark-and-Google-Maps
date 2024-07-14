# Network-Tracking-using-Wireshark-and-Google-Maps
Network Tracking using Wireshark and Google Maps
Steps:
 Obtain IP Address:
 Access https://www.whatsmyip.org/ to find your current IP address.
Modify IP Address in Wireshark:
  Open Wireshark and filter the captured packets.
  Change the IP address to your current IP address.
  Generate KML Contents:

Once packets are captured, generate KML contents that will display network traffic locations.
Save KML File:

Save the generated KML contents to a file with a .kml extension.
Add KML File to Google Maps:

Navigate to Google My Maps.
Create a new map or open an existing one.
Click on "Import" and select the .kml file from your computer.
Once uploaded, the network traffic data will be displayed on the map.
Example Workflow:
Step 1: Obtain your IP address from https://www.whatsmyip.org/.

Step 2: Use Wireshark to capture network traffic.

Step 3: Modify the captured IP addresses to your current IP in Wireshark.

Step 4: Generate KML contents from Wireshark.

Step 5: Save the generated KML file with a meaningful name, such as network_traffic.kml.

Step 6: Log in to Google My Maps.

Step 7: Create a new map or open an existing one.

Step 8: Click on "Import" and select your saved .kml file.

Step 9: Once imported, view your network traffic data overlaid on Google Maps.

Notes:
Ensure you have Wireshark installed and configured correctly to capture and analyze network traffic.
The .kml file format is compatible with Google Maps for visualizing geographical data.
