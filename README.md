# Smart Ambulance Dispatch and Route Selection

## About the Project

Smart Ambulance Dispatch and Route Selection is a **Python-based project** designed to demonstrate how algorithms can help select a suitable ambulance and find the shortest route during medical emergencies.

The system considers patient location, ambulance availability, and route distance. It uses algorithmic techniques to demonstrate how emergency dispatch decisions can be made efficiently.

## Problem Statement

During emergencies, delays in ambulance selection and route planning can affect response time. Selecting only the nearest ambulance may not always be the best option. This project demonstrates an algorithm-based approach to ambulance selection and route calculation.

## Objectives

- Select a suitable available ambulance.
- Give higher priority to critical emergencies using a Priority Queue.
- Calculate the shortest route using Dijkstra's Algorithm.
- Display the selected ambulance, route, distance, and estimated travel time.

## Key Features

- Patient location input.
- Emergency severity selection: Critical, Urgent, and Stable.
- Ambulance availability checking.
- Shortest-route calculation.
- Ambulance selection based on route distance.
- Estimated travel-time calculation.
- Message displayed when no ambulance is available.

## Technologies Used

- **Programming Language:** Python
- **Development Tool:** Visual Studio Code
- **Algorithms:** Dijkstra's Algorithm and Greedy Selection
- **Data Structure:** Priority Queue (Heap)
- **Data Storage:** Python dictionaries and lists

## How It Works

1. Enter the patient's location.
2. Select the emergency severity.
3. Add the emergency to the Priority Queue.
4. Check which ambulances are available.
5. Calculate routes using Dijkstra's Algorithm.
6. Select the available ambulance with the shortest calculated route.
7. Display the ambulance, route, distance, and estimated travel time.

## Algorithms Used

### 1. Dijkstra's Algorithm
Finds the shortest path between an ambulance's location and the patient's location in the simulated road network.

### 2. Priority Queue
Demonstrates how emergency requests can be prioritized according to severity.

### 3. Greedy Selection
Selects the currently best available ambulance based on the calculated route distance.

## How to Run the Project

**Requirements:** Python 3 and Visual Studio Code.

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open the terminal.
4. Run the Python file:

```bash
python main.py
```

Replace `main.py` with the actual Python filename if it is different.

5. Enter the patient location and emergency severity when prompted.
6. View the selected ambulance and calculated route.

## Expected Output

The program displays:
- Available ambulance route calculations.
- Selected ambulance.
- Shortest calculated route.
- Route distance.
- Estimated travel time.
- Dispatch status.

## Limitations

This project is an algorithm-based prototype that uses a simulated road network. It does not currently use live GPS tracking or real-time traffic data, and it has not been deployed with real ambulance services. Estimated travel time is based on the speed assumption in the prototype.

## Future Enhancements

- Real-time GPS tracking.
- Live traffic integration.
- Dynamic route updates.
- Hospital availability information.
- Coordination of multiple ambulances.
- Integration with real emergency services after appropriate testing and validation.

## Conclusion

Smart Ambulance Dispatch and Route Selection demonstrates the practical application of Design and Analysis of Algorithms (DAA) in emergency management. By combining shortest-path calculation, priority handling, and ambulance availability checking, the prototype illustrates how algorithm-based systems can support emergency dispatch decisions.

## Team Members

- Kusuma — 25MVCEMR0615
- Akshaya — 25MVCEMR0569
- Keerthana — 25MVCSMR0622
- Mahesh — 25MVCSMR0546

**Department:** CSE AIML  
**College:** Malla Reddy Technical Campus

## Disclaimer

This project is an academic prototype for demonstration purposes only. It should not be used to make real-world emergency dispatch decisions.
