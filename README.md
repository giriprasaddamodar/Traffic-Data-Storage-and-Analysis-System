# Traffic-Data-Storage-and-Analysis-System

Traffic Data Storage and Analysis System (Using Java and HDFS)
This project focuses on storing and analyzing large-scale traffic data using HDFS (Hadoop Distributed File System) and Java. It helps in retrieving and processing traffic data efficiently without using MapReduce or Spark.

🚦 Project Overview
Objective: Store, retrieve, and analyze traffic data efficiently using HDFS and Java.
Use Case: A city wants to analyze vehicle movement, congestion levels, and traffic patterns to optimize road infrastructure and reduce traffic jams.
Technologies Used:
* Java (Basic OOP concepts) – For handling data processing.
* HDFS (Hadoop Distributed File System) – To store large-scale traffic data.
* CSV Files – As a structured data format for traffic records.

🛠️ Project Implementation Steps
Step 1: Setting Up HDFS
First, we create an HDFS directory to store traffic data.

Step 2: Traffic Data Example (CSV File)
A CSV file (local_traffic_data.csv) contains traffic details:

Timestamp, Location, Vehicle_Count, Avg_Speed (km/h)
2025-02-24 08:00, Main Road, 120, 40
2025-02-24 09:00, Highway, 300, 80
2025-02-24 10:00, City Center, 150, 30

Step 3: Java Code to Read Data from HDFS
We write a Java program to read and process the stored data.

Java Code: Read Traffic Data from HDFS

What this Java code does:
✅ Reads traffic data from HDFS.
✅ Displays location, vehicle count, and speed in the terminal.

Step 4: Running the Program
Compile and run the program using Hadoop libraries.

📊 Expected Output

Traffic Data Analysis:
Location: Main Road, Vehicle Count: 120, Speed: 40 km/h
Location: Highway, Vehicle Count: 300, Speed: 80 km/h
Location: City Center, Vehicle Count: 150, Speed: 30 km/h

🔍 Conclusion
This project stores traffic data in HDFS and retrieves/analyzes it using Java.
Can be expanded with real-time data (IoT sensors, API integration).
Helps in urban planning, congestion analysis, and traffic prediction.

💡 Next Steps:
Add Data Visualization (Power BI, Python Matplotlib) or Real-time Traffic Sensors to this project? 🚦📊

