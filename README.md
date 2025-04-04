# Dell Port Allocation Optimizer

This application simulates Dell's weekly Finished Goods Inventory (FGI) shipments and helps supply chain analysts allocate containers dynamically across available ports, track shipping costs, monitor delivery time, evaluate congestion risks, and predict outcomes.

## How to Launch the Application

You have two options to launch the application:

### Option 1: Direct Browser Launch (Windows)

1. Double-click the `launch.bat` file
2. This will open the application in your default web browser

### Option 2: Using Node.js Server (Cross-platform)

1. Make sure you have [Node.js](https://nodejs.org/) installed
2. Open a terminal/command prompt in this directory
3. Run the command: `node server.js`
4. The application will automatically open in your default browser at http://localhost:3000

If it doesn't open automatically, you can manually navigate to http://localhost:3000 in your browser.

## Features

- Interactive port allocation with +/- controls
- Real-time calculation of costs, lead times, and utilization
- Interactive map with shipping routes
- Visualization of air vs ground freight distribution
- Cost vs time gradient analysis
- Port scoring system based on multiple factors
- Automatic optimal allocation based on port scores

## System Requirements

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- For server option: Node.js installed

## Using the Application

1. Adjust container allocations using the +/- buttons or by entering values directly
2. Modify port costs and lead times as needed
3. Set congestion levels for each port
4. View the updated metrics, charts, and map in real-time
5. Click "Calculate Optimal Allocation" to automatically distribute containers based on port scores
6. Click "Reset Allocation" to return to default values

The total allocation cannot exceed 50 containers per week. 