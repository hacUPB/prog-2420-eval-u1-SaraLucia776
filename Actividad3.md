# Pseudocódigo ejemplo 6
- Definición del problema:
Definir cuantos años, meses y días tiene una persona actualmente, basándose en su fecha de nacimiento. 
- Variables:

  "Día", "Mes", "Año", "Día_actual", "Mes_actual", "Año_actual", "Edad" 


## Pseudocódigo 
Inico 

    Leer "Día", "Mes", "Año"

    Leer "Día_actual","Mes_actual", "Año_actual"

    Definir "Edad" como ("Año_actual" - "Año")
    
        Si "Mes_actual">= "Mes" entonces

            Si "Día_actual">= "Día" entonces 
    
                Imprimir "Edad"
        Cerrar si 
        Si "Mes_actual"< "Mes" entonces

            Si "Día_actual"< "Día" entonces 

                Imprimir "Edad -1"
        Cerrar si

        Si "Mes_actual"= "Mes" entonces
    
            Si "Día_actual"= "Día" entonces

                Imprimir "Feliz cumpleaños"
                Imprimir "Edad"
    Cerrar si 
Fin




  
  
