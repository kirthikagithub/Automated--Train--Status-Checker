# Automated--Train--Status-Checker
The program is designed to retrieve and present the live status of a specified train using Python and an external web API.
API Integration:

The script utilizes the requests library to interact with a web API (https://rappid.in/apis/train.php) that provides live train status information. The API is queried with a specific train number, and the response is processed.
User-Defined Function:

The get_live_train_status function encapsulates the logic for making the API request and parsing the JSON response. It takes a train number as input and returns a dictionary containing relevant information.
Displaying Train Status:

The script is configured to check the live status of a train with the train number "16530" by default. The retrieved data includes the train name, current station details, distance from the starting point, timing, delay, platform number, and halt timing.
Structured Output:

The program organizes the retrieved information in a structured manner, printing details for the current station, such as station name, distance, timing, delay, platform number, and halt timing. Additionally, it displays the overall message and the time of the last update.
Informative Output:

The output is designed to be user-friendly and informative, providing essential details about the train's current status. The script aims to assist users in staying informed about the progress of a specific train in real-time.
Default Train Number:

The program is set to check the live status of train number "16530" by default. Users can modify the train number by changing the train_number variable in the script.
