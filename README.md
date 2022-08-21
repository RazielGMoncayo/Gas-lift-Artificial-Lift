# **Gas lift (Artificial Lift)**
I did this program when I was a student in 2021 and I used Matlab App Designer with my educational license.   
It's a Continuous-flow Gas Lift problem and I took valves CAMCO type AK without spring.   
_____   
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
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/First_plot.png?raw=true)
### First and second Table
*Control fluid gradient line*
Program   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/First_plot.png?raw=true)

### Valves calibration
*Pressure*   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/First_plot.png?raw=true)
*Temperature*   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/First_plot.png?raw=true)

### Relación de calores específicos en función de la temperatura y la densidad relativa
Relationship of specific heats as a function of temperature and relative density   
Plot   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/First_plot.png?raw=true)
Program   
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Graphic%20interface%20pictures/First_plot.png?raw=true)
### CAMCO table
![alt text](https://github.com/RazielGMoncayo/Gas-lift-Artificial-Lift/blob/master/Plots/CAMCO%20table.jpg?raw=true)
____
## About code
I'll be really honest, when I did this program I didn't understand loops enough, and I didn't use that.   
   
In the Valves calibration, I used **polyxpoly** to know the intersection between two lines.   

And the steps that I followed was the established ones in this sistem.   

## Graphic interface
