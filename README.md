This project analyzes Bitcoin price changes based on trade data received from WebSocket feeds. The data is published and processed through a pipeline built using Apache Beam, leveraging Google Cloud Dataflow as the execution engine. The pipeline calculates the average price, total quantity of Bitcoin traded, and the total value of Bitcoin purchases over an hourly (or minute) window. The processed data is then stored in Firestore for further analysis and tracking.