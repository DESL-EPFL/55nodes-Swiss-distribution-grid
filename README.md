# 55nodes-Swiss-distribution-grid
The file is mat. file and it consists of grid data, location of node, installed PV panel capacity, installed hydro power plant capacity. Also it has load profiles of 8 typical day-types, solar irradiation data of 8 typical day-types, and hydro generation of 8 typical day-types. 
1. Array "Linedata" shows the line data of the 55 nodes distribution grid. The columns represet as follows:   
      1st and 2nd columns - node numbers connected to each other by line. 
      3rd  column - resistance(r) of the line(Ohm/km)
      4th column : reactance(x) of the line(Ohm/km)
      5th column : susceptance(b) of the line(microS/km) 
      6th column : line ampacity(A)
      7th column : line length(km)
      8th column : Type of line (1-overhead line, 2-underground cable)
2. Nodes_with_Load : Node number where the load consumption is located
3. Nodes_with_PV_capacity :
      1st column : Nodes with PV panel
      2nd column : Corresponding PV capacity (kW)
4. Nodes_with_HP_capacity :
      1st column : Nodes with hydro power plants
      2nd column : Corresponding hydro power plants capacity (kVA)
5. ActiveLoad_data : Active load data of 43 nodes (corresponding to the node number in 'Nodes_with_Load')
      96 dispatch time interval x 8 typical day-types (kW)      
6. ReactiveLoad_data : Reactive load data of 43 nodes (corresponding to the node number in 'Nodes_with_Load')
      96 dispatch time interval x 8 typical day-types (kVAR)
7. PV_data : Solar irradiation data of 96 dispatch time interval x 8 typical day-types (W/m2)
8. HP_active_data : Hydro power active power generation data of 96 dispatch time interval x 8 typical day-types (kW)
9. HP_reactive_data : Hydro power reactive power generation data of 96 dispatch time interval x 8 typical day-types (kVAR) 
