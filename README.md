# flight-delay-prediction
La puntualidad de los vuelos es un factor cr´ıtico para la satisfacci´on de los pasajeros y la eficiencia
en la industria a´erea. Sin embargo, es com´un que los vuelos experimenten atrasos, lo que puede tener
consecuencias negativas tanto para los pasajeros como para las aerol´ıneas. Los atrasos pueden generar
costos adicionales para las aerol´ıneas, as´ı como la necesidad de reprogramar vuelos y pagar compensaciones a los pasajeros afectados. Asimismo, ellos pueden experimentar estr´es y p´erdida de tiempo debido a
los atrasos, lo que puede afectar su experiencia de viaje y su fidelidad a las aerol´ıneas.
En este contexto, vamos a desarrollar distintos modelos de machine learning con el objetivo de predecir atrasos en los vuelos y, por lo tanto, permitir que las aerol´ıneas tomen medidas proactivas para
evitarlos o mitigar sus consecuencias. Estos modelos usar´an datos hist´oricos de los vuelos, en conjunto
con factores externos como el clima y las distancias.
Para nuestro desarrollo, se consideran a los vuelos como atrasados cuando la diferencia entre la hora
para la cual el vuelo estaba programado y la hora en la que realmente sali´o es mayor a 15 minutos. Este
criterio ha sido fijado por parte del cliente. Las consecuencias de que un vuelo se retrase menos de 15
minutos no tienen un gran impacto, mientras que si un vuelo se retrasa m´as de 15 minutos, ya empieza
a producir los problemas mencionados anteriormente.
