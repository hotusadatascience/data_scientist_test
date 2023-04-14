# Grupo Hotusa - Data Scientist Test

El director de Revenue Management de un hotel nos comenta que las cancelaciones tienen un impacto negativo y se pregunta si con esto del Machine Learning y la Inteligencia Artificial seríamos capaces de predecir que reservas van a cancelar y cuáles no. 

El director quiere poner en marcha este modelo para poder realizar overbooking (llenar el hotel por encima del inventario total disponible con el objetivo de ocupar aquellas reservas que se van a cancelar). El hotel está en el centro de Lisboa y en la misma ciudad el grupo hotelero tiene varios hoteles, por lo que no hay ningún riesgo en llenar el hotel más de la cuenta y enviar el exceso de reservas a otros hoteles en la ciudad.

## Descripción de la tarea

El dataset (**hotusa_cancellations.csv**) con el que trabajar contiene las siguientes columnas:
- *HotelId*:
- *ReservationStatusDate*: Fecha en la que se realizó la reserva
- *ArrivalDate*: Fecha de inicio de la reserva
- *LeadTime*: Antelación (días entre la generación de la reserva hasta la fecha de inicio de ésta)
- *StaysInWeekendNights*: Número de noches entre semana
- *StaysInWeekNights*: Número de noches el fin de semana
- *Adults*: Número de adultos en la reserva
- *Children*: Número de niños en la reserva
- *CustomerType*: Tipo de cliente
- *ADR*: Average Daily Rate (precio medio por reserva. Precio total de la reserva dividido por el número de noches)
- *Meal*: Tipo de Alojamiento 
- *Country*: País de procedencia del cliente
- *Company*: Compañía del cliente
- *ReservedRoomType*: Habitación reservada
- *IsRepeatedGuest*: Cliente repetitivo

Debes crear un report reproducible (en un notebook en Python o R) siguiendo estos pasos:
1. EDA sencillo y básico. 
 * ¿Qué variables parecen ser las más predictivas?
2. Preparación de los datos.
 * 
3. Construcción del modelo. 

Se valorará las explicaciones y insights que se detecten como también que las gráficas sean fáciles de leer. No es tanto escupir los datos, sino contar una historia con ellos. Este report lo debería poder leer tanto un perfil técnico como un perfil de negocio. 

## Entrega

Entrega tus resultados en notebook o en un link al repo en GitHub a: carlos.perez@eurostarshotelcompany.com 
