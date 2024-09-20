# DS1-project - Data Science I project

## Abstract
Este proyecto está enfocado en el análisis de un dataset de **reservas de hotel**, cuyo objetivo es predecir si una reserva será cancelada o no. El dataset contiene información detallada sobre las características de cada reserva, como el número de adultos, niños, noches de estancia (entre semana y fines de semana), el tipo de plan de comidas seleccionado, la necesidad de estacionamiento, el tipo de habitación reservada, y el tiempo de antelación entre la reserva y la llegada (lead time). También incluye el historial de cancelaciones previas del cliente, el número de solicitudes especiales y el precio promedio por habitación.

En la etapa de análisis exploratorio se investigarán patrones en los datos, la distribución de las variables y la posible relación entre las características y las cancelaciones. Posteriormente, se utilizarán estas variables para entrenar un modelo predictivo, cuyo objetivo será ayudar a los hoteles a anticipar cancelaciones, optimizar la asignación de recursos y mejorar la experiencia del cliente.

Resulta de interés el análisis ya que permitirá a los hoteles tomar decisiones más informadas, minimizar pérdidas asociadas a cancelaciones y ajustar su política de reservas en función de las tendencias identificadas.

Para llevar a cabo el procesamiento de los datos, se utiliza **Python** y sus librerías para Data Science (pandas, numpy, matplotlib y seaborn).

## Content
- Exploración y limpieza de los datos.
- Visualizaciones iniciales con matplotlib y seaborn.
- Entrenamiento de un modelo predictivo.

## Data Dictionary
- **Booking_ID** - Identificador único de cada reserva.
- **no_of_adults** - Número de adultos incluidos en la reserva.
- **no_of_children** - Número de niños incluidos en la reserva.
- **no_of_weekend_nights** - Número de noches de fin de semana (sábado o domingo) que el cliente reservó o se hospedó en el hotel.
- **no_of_week_nights** - Número de noches entre semana (lunes a viernes) que el cliente reservó o se hospedó en el hotel.
- **type_of_meal_plan** - Tipo de plan de comidas reservado por el cliente.
- **required_car_parking_space** - Indica si el cliente requiere un espacio de estacionamiento (0 = No ; 1 = Yes).
- **room_type_reserved** - Tipo de habitación reservada por el cliente, codificada por el hotel.
- **lead_time** - Número de días entre la fecha de reserva y la fecha de llegada al hotel.
- **arrival_year** - Año de llegada del cliente.
- **arrival_month** - Mes de llegada del cliente.
- **arrival_date** - Día del mes en que el cliente llegó o tenía programado llegar al hotel.
- **market_segment_type** - Segmento de mercado asignado a la reserva (por ejemplo, grupo de empresas, individual, etc.).
- **repeated_guest** - Indica si el cliente es recurrente (0 = No ; 1 = Yes).
- **no_of_previous_cancellations** - Número de reservas anteriores que fueron canceladas por el cliente antes de la reserva actual.
- **no_of_previous_bookings_not_canceled** - Número de reservas anteriores que no fueron canceladas por el cliente antes de la reserva actual.
- **avg_price_per_room** - Precio promedio por día de la reserva en euros. Los precios son dinámicos y varían.
- **no_of_special_requests** - Número total de solicitudes especiales realizadas por el cliente (por ejemplo, piso alto, vista, etc.).
- **booking_status** - Estado de la reserva, indica si fue cancelada o no.