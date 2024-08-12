- Definición del problema:
Cuanto debe cobrar el dueño de un estacionamiento por el uso de este a sus clientes

Dos primeras horas 5
Siguientes tres horas 4
Cinco siguientes horas 3
Después de diz horas 2 cada hora 

- Variables
Número_horas, "Costo" 

Inicio 
 Leer Número_horas
  Si Número_horas <= 2 
   "Costo"= (Número_horas * 5)
    Si no 
     Si 2 <Número_horas<=5
     "Costo"= ((Número_horas - 2)*4)+10
      Si no 
       Si 5< Número_horas<=100
        "Costo"= ((Número_horas - 5)*3)+22
         Si no 
          "Costo"= (Número_horas *2)
        Fin si 
      Fin si 
  Fin si 
Fin

- Definición del problema: 
Caunto es la cuaota mensual que debe pagar una persona por hacer una compra con su tarjeta de crédito
- Variables: 
Costo, Número_cuotas, Interés

Inicio 
 Leer Costo
 Leer Número_cuotas 
 Leer Interés 
  
