# Curso: Desarrollo de Apps para Android con Kotlin

A continuación se encuentra el indice de ejercicios desarrollados a lo largo del curso de desarrollo de aplicaciones para Android.

## Layouts
*Ejercicios relacionados con el uso de Layouts.*

1. **Linear Layout**.

    Ejercicio 01 | Ejercicio 02 | Ejercicio 03
    ------------ | ------------ | ------------
    ![Ejercicio 01](/images/linear_layout_01.png) | ![Ejercicio 02](/images/linear_layout_02.png) | ![Ejercicio 03](/images/linear_layout_03.png)

    - Recursos [Descargar](https://drive.google.com/drive/folders/1OLs2PbGsdbz_6bhOgm6dHVstCnAQaSpx?usp=sharing)

    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC01-LinearLayout)
    
2. **Grid Layout**.

    Ejercicio 01 | Ejercicio 02 | Ejercicio 03
    ------------ | ------------ | ------------
    ![Ejercicio 01](/images/grid_layout_01.png) | ![Ejercicio 02](/images/grid_layout_02.png) | ![Ejercicio 03](/images/grid_layout_03.png)

    - Recursos [Descargar](https://drive.google.com/drive/folders/1mGOVU0_sDs5Kj4_ncS-8p4aVTUjLKl-0?usp=sharing)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC02-GridLayout)
    
3. **Relative Layout**. 

    Ejercicio 01 | Ejercicio 02 | Ejercicio 03
    ------------ | ------------ | ------------
    ![Ejercicio 01](/images/relative_layout_01.png) | ![Ejercicio 02](/images/relative_layout_02.png) | ![Ejercicio 03](/images/relative_layout_03.png)

    - Recursos [Descargar](https://drive.google.com/drive/folders/1NKtqumRxfYHiykprGTlG40TSCVrz_4AM?usp=sharing)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC03-RelativeLayout)

4. **Constraint Layout**.

    Ejercicio 01 | Ejercicio 02 | Ejercicio 03
    ------------ | ------------ | ------------
    ![Ejercicio 01](/images/relative_layout_01.png) | ![Ejercicio 02](/images/relative_layout_02.png) | ![Ejercicio 03](/images/relative_layout_03.png)

    - Recursos [Descargar](https://drive.google.com/drive/folders/1WSuUHvgNqGWShcbL5dC6bDu9MIrupKAM?usp=sharing)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC04-ConstraintLayout)

## Kotlin.
*Ejercicios relacionados con la sintaxis de Kotlin.*

5. **Calculator**. 
    - Recursos [Descargar](https://drive.google.com/drive/folders/1dvYgmrVyyGrKCkW_7eT5ByUeHP8UbfmS?usp=sharing)
    - Ejercicio en Desarrollo [Ir al Repo](https://github.com/Nemesis2074/AC05-Working-Calculator)
    - Ejercicio Completado [Ir al Repo](http://bit.ly/2Zj2KPG)

## Activities & Fragments
*Ejercicios relacionados con el uso de actividades y fragmentos*

6. **Activities**. 
    - Recursos [Descargar](https://drive.google.com/drive/folders/1GjAWQ3pS1owFTHX0fXYbf2hYHl3gmsAd?usp=sharing)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC06-Activities)

7. **Fragments**. 
    - Recursos [Descargar](https://drive.google.com/drive/folders/1VIqkVM_kmGmPeukkCOCXwlbKY-hzECrO?usp=sharing)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC07-Fragments)

8. **Who's That Pokemon**. 
    - Recursos [Descargar](https://drive.google.com/drive/folders/1QMR2gWddWBBz0qyYUxBUmOMmSAP6PwDA?usp=sharing)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC08-Pokemon)

## Controles Avanzados
*Ejercicios relacionados con el uso de los controles avanzados de Android para mostrar contenido en pantalla.*

9. **ListView**.
    - Recursos [Descargar](https://drive.google.com/drive/folders/1G9ExgtsTVcrO8JXTIACHKlPsH_-Kp91N?usp=sharing)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC09-ListView)
  
10. **GridView**.
    - Servicio: [Ver JSON](https://mi-docencia-benv.web.app/demos/kitties.json)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC10-Working-GridViewDemo)

11. **RecyclerView**
    - Servicio: [Ver JSON](https://mi-docencia-benv.web.app/demos/contacts.json)
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC11-Working-RecyclerView)
  
13. **ViewPager**
    - Ejercicio Completado [Ir al Repo](https://github.com/Nemesis2074/AC12-ViewPager)

## Aplicación Final
*Aplicación completa cuyo objetivo es aplicar los conocimientos obtenidos a lo largo del curso*

**Secciones:**

Las secciones que deberá tener la App son:

    - En Cines.
    - Próximamente.
    - Noticias
    - Detalle de Película.
    - Detalle de Noticia.

**Servicios:**

La información para cada sección se deberá obtener de los siguientes servicios:

Servicio   | URL         |  Método | Parámetros | Comentarios                   |
-----------|-------------|---------|------------|-------------------------------|
Noticias   | [/news.php](https://androiddevcourse.000webhostapp.com/news.php)   | GET     |            |                               |
Películas  | [/movies.php](https://androiddevcourse.000webhostapp.com/movies.php) | POST    | type       | 1 = En Cines 2 = Próximamente |

Los servcios se encuentran bajo el dominio: https://androiddevcourse.000webhostapp.com

**Estructura JSON**

Películas:

    {
        "id": 1,
        "name": "Ad Astra",
        "director": "James Gray",
        "synopsis": "Astronaut Roy McBride (Brad Pitt) travels to the outer edges of the solar system to find his missing father
        and unravel a mystery that threatens the survival of our planet. His journey will uncover secrets that challenge the
                nature of human existence and our place in the cosmos.",
        "poster":
        "https://resizing.flixster.com/DFPIRWYX3mL7y9pryZ0LSEJTuqM=/fit-in/200x296.2962962962963/v1.bTsxMzEzMTgyNjtwOzE4MTk2OzEyMDA7OTAwOzEzNTA",
        "trailer": "https://www.youtube.com/watch?v=gaf-zgnlNLg",
        "preview":
        "https://resizing.flixster.com/WIWyWZ10_Bd6OFzFhdybdyIWtMc=/720x290/v1.bjsyMzI5Njk0O2o7MTgyNTE7MTIwMDs0MDk2OzE3MTY",
        "average_rating": 7.68,
        "fresh": 191,
        "rotten": 42,
        "audience_score": 50,
        "audience_total_ratings": 624,
        "audience_average_rating": 3.09
    }

Noticias:

    {
        "id": 1,
        "date": 1568973600,
        "title": "Kit Harington ya está rodando 'The Eternals', su entrada en el Universo Cinematográfico Marvel",
        "summary": "Tras algunos rumores, en la D23 de Disney se confirmó que Kit Harington se unía al ya de por sí
    impresionante elenco de 'Eternals'.",
        "thumbnail": "https://img.ecartelera.com/noticias/fotos/56400/56482/1.jpg",
        "content": "Tras algunos rumores, en la D23 de Disney se confirmó que Kit Harington se unía al ya de por sí
    impresionante elenco de 'Eternals'. Marvel confirmó que el actor de 'Game Of Thrones' daría vida a Dane Whitman, quien
    es conocido como Black Knight en el universo de la casa de las ideas. Ahora, y gracias a la publicación de una de sus
    compañeras de reparto, hemos podido ver el nuevo look que el actor lucirá en esta nueva aventura cinematográfica.\n\nHa
    sido la actriz Salma Hayek la que nos ha sorprendido a todos con su publicación en Instagram junto a Harington. Hayek
    será la encargada de interpretar a la líder de los Eternos, Ajak. Originariamente este miembro es representado como un
    hombre, pero para la cinta el estudio ha decidido cambiar el género de este personaje de cómics y ofrecérselo a la
    intérprete mexicana\n\n\"No puedo creer que esté trabajando con Jon Snow! Kit eres el mejor!!!\", escribía entusiasmada
    la actriz. Gracias a esta instantánea, podemos confirmar que el mítico guarda de la noche se ha unido ya al rodaje de la
    próxima cinta de Marvel. 'Eternals' nos cuenta la historia de un grupo de super-humanos creados genéticamente que tienen
    el don de la larga vida. La cinta se estrenará el 6 de noviembre de 2020."
    }

**Validaciones**

Para el caso del Tomatómetro:

- Podrído: Si el procentaje es menor al 60%
- Fresco: Si el porcentaje es mayor o igual al 60%
- Certificado Frescura: Si e porcentaje es mayor al 75% y el número total de reviews es mayor a 40
- No disponible: Si no tiene reviews

Para el caso de la Audiencia:

- Podrído: Si el procentaje es menor al 60%
- Fresco: Si el porcentaje es mayor o igual al 60%
- No disponible: Si no tiene reviews

**Recursos:**

Los iconos necesarios para la App se enceuntran aquí: [Descargar](https://drive.google.com/drive/folders/1GzW1wKFAGLgk28cB3ecJCLEjKhiKcwbx?usp=sharing)

**Pantallas:**

Estas son las pantallas de ejemplo de las secciones que deberá tener la App:

<img src="/images/movies_screen_01.png" width="200"> 
<img src="/images/movies_screen_02.png" width="200">
<img src="/images/movies_screen_03.png" width="200">
<img src="/images/movies_screen_04.png" width="200">
<img src="/images/movies_screen_05.png" width="200">
