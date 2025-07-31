A Python project that extracts carrier and location information from a phone number and displays it on an interactive map using Folium and OpenCage API.

🔧 Features
✅ Parses international phone numbers and identifies location

✅ Retrieves carrier/network provider information

✅ Geocodes the location into latitude and longitude coordinates

✅ Generates an interactive HTML map with a location marker using Folium

🛠️ Tech Stack
Python 3

phonenumbers

OpenCage Geocoder API

Folium

HTML / Leaflet.js (for map rendering)

🚀 How to Run
Install dependencies:

bash
Copy
Edit
pip install phonenumbers folium opencage
Replace the phone number in myphone.py or allow user input.

Run the script:

bash
Copy
Edit
python main.py
View the map:
Open mylocation.html in your browser to see the tracked location.

🔑 API Key
You will need an OpenCage API key. Replace the placeholder in main.py:

python
Copy
Edit
key = "YOUR_API_KEY"
📂 Files
main.py – Core logic to parse number, get location/carrier, generate map

myphone.py – Stores the test number (can also be taken via input)

mylocation.html – Auto-generated interactive map output
