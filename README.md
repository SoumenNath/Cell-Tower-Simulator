# Cell-Tower-Simulator

This program is a simulator for vehicles entering in and out of cell phone tower zones. The code makes use of multiple threads and processes to allow multiple vehicles to connect to various towers. Each tower and each vehicle running is a different process.
The following is an image of the simulation. The large open circles represent the range of the different cell towers whereas the smaller cirlces represent the vehicles. The cell towers remain stationary during the simulation but the vehicles move around in different speeds and directions. This program demonstrates the client and server interaction in C. The server that is running in the background is the simulator.c file that calls upon the cellTower.c file that handles client requests. The clients in this case are the different vehicles. 
When a vehicle enters the range of a cell tower, communicate will start between these entities. This communication will stop once the cell tower recognizes that the vehicle has left its range.
![Simulation Image](https://github.com/SoumenNath/Cell-Tower-Simulator/blob/master/simImage.png)
Skeleton code provided by Mark Lanthier.
