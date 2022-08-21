# **Gas lift (Artificial Lift)**
I did this program when I was a student in 2021 and I used Matlab App Designer with my educational license.   
It's a Continuous-flow Gas Lift problem and I took valves CAMCO type AK without spring.   
____
## **Input Data and units**
*The technical names in English and Spanish.* 

*qo* = Oil flow rate / Gasto del aceite [bpd]   
*Pdi* = Available pressure / Presion disponible [psi]   
*Pso* = Operating pressure / Presion de operacion [psi]   
*Pwh* = Well Head Pressure / Presion en la cabeza de pozo [psi]   
*γg iny* = Injection Gas Density / Densidad del Gas de Inyección [adm]   
*ρ FC* = Control FLuid Density / Desnisidad del fluido de Control [adm]   
*ɸT.R.* = Casing Diameter [in] / Diametro de la Tuberia de Revestimiento [pg]    
*ɸT.P.* = Production pipe [in] / Diametro de la Tuberia de Produccion [pg]   
*IP* = Productivity Index [psi/bpd] / Indice de productividad [bpd /psi]   
*Prof Emp* = Packer Depth [ft] / Profundidad del Empacador [pies]   
*Twh* = Well Head Temperature / Temperatura en la cabeza de pozo [°F]    
*Tfondo* = Bottomhole temperature / Temperatura de fondo [°F]   
*ΔP* = Pressure Differential in the Operating Valve / Diferencial de Presion en la Valvula de Operacion [psi]   
*T.C Taller* = Calculated Temperature in the workshop / Temperatura Calculada en el Taller [°F]   
*RGAN* = Gas Oil Ratio [bl/ft3] / Relacion Gas Aceite [pc/bl]   
*RGAT* = Working Gas Oil Ratio [bl/ft3] / Relacion Gas Aceite de Trabajo [pc/bl]   
*ρ oil* = Oil Density / Densidad del Aceite [°API]   
*Pws* = Pressure bottomhole static / Presión de fondo estática [psi]   
*%Agua* = Water percentage / Porcentaje de agua [adim]   
_____
## Graphic interface
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/Graphic%20interface%201.png?raw=true)
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/Graphic%20interface%202.1.png?raw=true)
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/Graphic%20interface%203.1.jpg?raw=true)
_____
## **Results**   
### First plot   
*Gradients for oil-saltwater mixtures*      
Plot   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Plots/gradientes%20para%20mezclas%20de%20aceite-agua%20salada.jpg?raw=true)
Program   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/First_plot.png?raw=true)

### Second plot   
*Weigth of gas column*   
Plot   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Plots/weight%20of%20gas%20column.jpg?raw=true)   
Program   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/Second_plot.png?raw=true)   

### Valves calibration
*Pressure and Temperature Results*   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/Pressure%20and%20Temperature.png?raw=true)   
In the Valves calibration, I used **polyxpoly** to know the intersection between two lines.   

### Relationship of specific heats as a function of temperature and relative density      
Plot   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Plots/Relaci%C3%B3n%20de%20calores%20espec%C3%ADficos%20en%20funci%C3%B3n%20de%20la%20temperatura%20y%20la%20densidad%20relativa.jpg?raw=true)
Program   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/Gas%20flow%20rate.png?raw=true)
### CAMCO table
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Plots/CAMCO%20table.jpg?raw=true)
____



