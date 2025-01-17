# User Location Data Analysis

This project demonstrates a sample data analysis process on user location data. The data contains information about the venues visited by users along with timestamps, and it covers the period from 16/11/2023 to 16/12/2023.

## Project Steps

### Step 1: Data Visualization
Visualize the users' data to understand the scope and distribution of the given data. This step helps in identifying patterns and anomalies in the dataset.
![image](https://github.com/user-attachments/assets/6cb71031-9d94-4930-8db5-8eafdf0e20f0)
![image](https://github.com/user-attachments/assets/51f63664-dc01-47e8-9e46-001714361364)
![image](https://github.com/user-attachments/assets/c4b45702-4159-4474-bcc8-49064b6831d1)


### Step 2: Grouping Users by Visiting Behavior
Group users based on their visiting behavior of different types of venues and different datetime of a month. This helps in understanding user preferences and trends over time.
![image](https://github.com/user-attachments/assets/f590b02d-3cf2-400c-b381-6e85599bee44)


### Step 3: Clustering Users with Weighing Mechanism
Cluster users based on their visiting behavior with a weighing mechanism where older visits have lower weights and newer visits have higher weights. This step emphasizes recent behavior while still considering older visits.
![image](https://github.com/user-attachments/assets/f510bfe6-3c95-4cfc-9376-717d6a06d724)


### Step 4: User Qualification Identification
Identify each user based on specific qualifications:
- **Sun lover**: Prefers visiting venues during the day.
- **Moon lover**: Prefers visiting venues at night.
- **Weekend lover**: Prefers visiting venues on weekends.
- **Weekday lover**: Prefers visiting venues on weekdays.
- **Wine lover**: Prefers visiting wine venues.
- **Bar lover**: Prefers visiting bars.
- **Pub lover**: Prefers visiting pubs.
- **Pastery lover**: Prefers visiting pastry shops.
- **Coffee lover**: Prefers visiting coffee shops.
![image](https://github.com/user-attachments/assets/16ae2de1-5d37-4179-b4bb-c1032e05f422)


## Data Files
- `data_20.json`: Contains user location data for a smaller set of users.
- `data_100.json`: Contains user location data for a larger set of users.

For this project, the `data_20.json` file is used to demonstrate the analysis process. However, the `data_100.json` file can be used to test the algorithm performance on a larger scale of data.

## Usage
To run the analysis, execute the Jupyter Notebook `assignment.ipynb` which contains all the steps and visualizations.

## Repository Structure
- `data/`: Directory containing the JSON data files.
- `assignment.ipynb`: Jupyter Notebook with the data analysis steps and visualizations.
- `README.md`: This readme file.


