# Pseudocódigo problema 6
- Definición del problema:
Definir cuantos años, meses y días tiene una persona actualmente, basándose en su fecha de nacimiento. 
- Variables:
"Día", "Mes", "Año", "Día_actual", "Mes_actual", "Año_actual", "Edad" 

## Pseudocódigo 
```
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
```

# Pseudocódigo problema 1 
- Definición del problema: 
Determinar si Ana aprobó su exámenes finales
- Variables:
"Nota_materia", "Cantidad_materias", "Nota_total","Notas_sumadas", "Promedio"

## Pseudocódigo
```
Inicio 

  Leer "Cantidad_materias"
  Para cada materia 
    Leer "Nota_materia"
    Sumar cada "Nota_materia"
    "Notas_sumadas" = "Nota_total"
  Fin para 

 "Promedio"= "Notal total"/"Cantidad_materias"
  
  Si "Promedio" <= 3.0 
     Imprimir "Exámenes fianles aprobados"
    Si no 
      Imprimir "Exámenes finales reprobados"
  Cerrar si 
Fin
```

# Pseudocódigo problema 2 
- Definición del problema: 
Javier necesita verificar si su número de identificación es válido usando una fórmula de verificación. 
- Variables: 
"Número_DNI", "Dígitos_DNI", "Suma_dígitos"

## Pseudocódigo 
```
Inicio 
 
 Leer "Número_DNI"

 Leer "Dígitos_DNI"

 Sumar "Dígitos_DNI"
  
  Si "Suma_dígitos" ∈ múltiplo de 10 
    Imprimir "DNI válido"
    Si no 
      Imprimir "DNI inválido"
  Cerrar si 
Fin 
``` 
  
