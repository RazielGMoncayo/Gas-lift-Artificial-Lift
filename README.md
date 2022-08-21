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

Program   

### Second plot   
*Weigth of gas column*   
Plot   

Program   
### First and second Table
*Control fluid gradient line*
Program 

### Valves calibration
*Pressure*   

*Temperature*   
### Relación de calores específicos en función de la temperatura y la densidad relativa
Relationship of specific heats as a function of temperature and relative density   
Plot   

Program   

### CAMCO table

____
## About code
I'll be really honest, when I did this program I didn't understand loops enough, and I didn't use that.   
   
In the Valves calibration, I used **polyxpoly** to know the intersection between two lines.   

And the steps that I followed was the established ones in this sistem.   

## Graphic interface
