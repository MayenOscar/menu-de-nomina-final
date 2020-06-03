# menu-de-nomina-final
aquí esta el código del menú de nomina finalizado 
#include <stdio.h>

int main()
{
    int x;
    printf("Bienbenido \n");
    printf("Eliga una opcion\n");
    printf("1- Factueas \n2- Control de inventario \n3- Cuentas por cobrar\n4- Cuentas por pagar\n5- cotizaciones \n6-Nomina de pago \n7- Recursos hunamos \n8-control de Acceso \n9- Ordenes de compras \n10- Control de pedidos \n11- Salir \n ");
    scanf("%d",&x);
    switch(x)
    {
        case 1:
            printf("Fracturas \n");
           
            break;
        case 2:
            printf("Control de inventario \n");
            
            break;
        case 3:
            printf("Cuentas por cobrar\n");
            
            break;
        case 4:
            printf("Cuentas por pagar \n");
            
            break;
        case 5:
            printf("Cotizaciones \n");
            
            break;
        case 6:
            printf("nomina de pago\n");
            
            break;
        case 7:
            printf("Recursos humanos\n");
            
        case 8:
            printf("Control de acceso \n");
            
            break;
        case 9:
            printf("Ordenes de compras\n");
           
            break;
        case 10:
            printf("Control de pedidos \n");
            
            break;
        case 11:
            printf("Salir \n");
            break;
            default:
            printf("opcion no valida\n");
    }
    return 0;
}
