# evaluacion_1
//Test para evaluar si una persona cumple con ciertas características para que no le vuelvan a romper el corazón.
#include <stdio.h>
#include <stdlib.h>

int main(){


    printf("A ver que tan preparado estas para continuar \n");
    //Pregunta 1
    printf("1.	¿Que buscas en una relacion? \n");
    printf("a) A) A alguien que me complemente al cien por cien y que cumpla con mi prototipo. \n  B) A alguien dispuesto a aprender de la relacion y hacerme mejorar a mi tambien. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'B'){
        puntos += 1;
    }
     //Pregunta 2
    printf("2.	Cuando piensas en tu ex, ¿como te sientes? \n");
    printf("a) A) Lo pase mal y todavía le guardo algo de rencor, pero ya no me obsesiona. \n B) Me entran todos los males en orden. A veces incluso ando de mitotero en sus redes sociales a ver si le va mejor que a mi. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'A'){
        puntos += 1;
    }
     //Pregunta 3
    printf("3.	¿Te gusta pasar tiempo a solas? \n");
    printf("a) A) No mucho. Me agobio o me aburro. Por eso siempre quedo con amigos. \n B) Muchas veces, si. Para mi es importante cuidarme y dedicar tiempo a mis aficiones mas alla de socializar con los demas. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'B'){
        puntos += 1;
    }
     //Pregunta 4
    printf("4.	Para ti una pareja es... \n");
    printf("a) A) Alguien que me alegre cuando estoy mal. Si no es capaz de animarme, es que algo va mal. \n B)	Alguien que me anime a mi mismo a cuidarme. Quiero que me apoye, pero ni puede ni debe solucionar todos mis problemas. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'B'){
        puntos += 1;
    }
     //Pregunta 5
    printf("5. ¿Te agobia compartir aspectos intimos personales? \n");
    printf("A)	Muchisimo. Soy muy reservado, y es complicado que me abra a una persona nueva. \n B) Un poco, pero con confianza podre compartir esas cosas sobre mi. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'B'){
        puntos += 1;
    }
     //Pregunta 6
    printf("6.	¿Que tipo de amor es mas relevante para ti? \n");
    printf("A)	El amor que proporciona una pareja, mis amigos, mi familia. En definitiva, los demás. \n B)	El amor propio. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'B'){
        puntos += 1;
    }
     //Pregunta 7
    printf("7.	Cuando piensas en compromiso, ¿que se te pasa por la cabeza? \n");
    printf("A)  Intimidad y confianza.  \n B) Agobio y presión. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'B'){
        puntos += 1;
    }
     //Pregunta 8
    printf("8.	Tu futuro ideal es… \n");
    printf("A)	Con alguien para compartir mi vida. \n  B)	Solo y sin ataduras \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'A'){
        puntos += 1;
    }
     //Pregunta 9
    printf("9.	Cuando ves a tus amigos con pareja, ¿que piensas? \n");
    printf("A)	lol, son todos domados \n B) dame de eso papadio porfavor. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'B'){
        puntos += 1;
    }
     //Pregunta 10
    printf("10.	¿Que harias si aparece en tu vida una persona que te atrae fisica, emocional e intelectualmente? \n");
    printf("A)	Negarla completamente y saber que no lo merezco. \n B)	Conocerle mejor. \n");
    scanf(" %c", &respuesta);
    if (respuesta == 'b'){
        puntos += 1;
    }
 if (puntos >=80){
    printf("\nValoren el amor muchachos, estás listo para esto");
 }
 else {
    printf ("\nYa ni pa la muela broder, ¿como vas a sacar menos de 80 aqui? ");
 }
    return 0;
}
