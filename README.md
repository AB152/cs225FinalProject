# CS225 Final Project
## Akshay Bhamidipati, Franklin Moy, Vish Gopal Sekar
- Building/Compiling this project:
  - Compile this project by running make in your terminal
    - Navigate to the directory containing this project and type "make" in your terminal.
- Running this project:
  - Type "./finalproj" to run the executable with no arguments.
    - This will run a DFS traversal with a source airport of ORD, a Prim's Minimum Spanning Tree starting from airport AAE, and a landmark path traversal starting from ORD to JFK with a stop in CMI.
  - Each algorithm will write its results to a file. (The program will tell you the file name in the terminal.)
  - You can also run each individual algorithm independently by typing the name of the algorithm after the executable:
    - DFS: "./finalproj dfs `[sourceAirport]`"
      - Note that airport codes are in all caps. An undefined output will occur if you use any lowercase characters.
      - If you only enter "./finalproj dfs", the program will run a DFS from every single airport.
    - Prims: "./finalproj prims"
      - The program will not run if you add more arguments on top of "prims". 
    - Landmark Path: "./finalproj landmark `[sourceAirport]``[destinationAirport]``[landmarkAirport]`"
      - Note that airport codes are in all caps. An undefined output will occur if you use any lowercase characters. 
      - landmarkAirport is the airport that the traversal will visit on its way from sourceAirport to destinationAirport.
- Dataset:
  - See [dataset_README.md](dataset/dataset_README.md) for more information on the OpenFlights dataset used. 