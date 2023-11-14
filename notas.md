![image](https://github.com/Lourdes-Cruz/Projects/assets/102762660/423296a7-0fb1-4706-8a86-8f5fc39f9e77)


#include <stdio.h>

int main() {
    double costoArticulo = 30.99;
    int listoEnviar = 0; // Utilizamos 0 para representar 'false' y 1 para 'true' en C

    if (costoArticulo > 24) {
        printf("!El valor del artículo es alto!\n");
    }

    if (listoEnviar == 1) {
        printf("Enviado\n");
    } else {
        printf("Pedido no listo\n");
    }

    return 0;
}
