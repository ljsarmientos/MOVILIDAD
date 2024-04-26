 #include <stdio.h>
 int main()

{ 
int opcion;
int ruta;

printf("\n\n Ingrese la ruta que desea buscar\n");

     printf("1.Rutas que funcionan los feriados\n");
     printf("2. A61 \n");
     printf("3. F61 \n");
     printf("0. Salir\n");  

    printf("\n Ingrese una opción:");
    scanf("%d",&opcion);
   
    if  (opcion==1)
    {
        printf("Rutas que funcionan los feriados A61 DIRECTO");
    
    }
    
    else if (opcion==2)
    {
        
    printf("2.A61 BANDERAS, CDS, CALLE 19, AVENIDA 39, CALLE 57, FLORES, CALLE 72");


    } 
    
    else if (opcion==3)
        
    printf("3. F61 CALLE 72, FLORES, CALLE 57, AVENIDA 39, CALLE 19, CDS, BANDERAS");
    
    }
