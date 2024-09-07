Este script simula un ecosistema utilizando dos modelos distintos: Daisyworld y Lotka-Volterra. 

El modelo Daisyworld se usa para simular la dinámica de temperatura global y la cobertura de margaritas blancas y negras en la superficie del planeta, 
mientras que el modelo Lotka-Volterra simula las poblaciones de conejos y zorros.

El código sigue los siguientes pasos:

Definición de Constantes: Se establecen constantes para los modelos Daisyworld y Lotka-Volterra, como albedos, tasas de crecimiento y parámetros iniciales.

Inicialización de Variables: Se inicializan las fracciones de superficie ocupada por margaritas y suelo, así como las poblaciones iniciales de conejos y zorros.

Funciones:

temperatura: Calcula la temperatura global en función del albedo.
tasa_crecimiento: Determina la tasa de crecimiento de las margaritas basándose en la temperatura.
calcular_biomasa: Calcula la biomasa total del ecosistema.
Simulación:

Se actualiza la constante solar y se calcula la temperatura global.
Se actualizan las fracciones de superficie cubierta por margaritas y se ajustan las poblaciones de conejos y zorros.
Se calcula y almacena la biomasa y producción de cada componente del ecosistema.
Visualización:

Se generan gráficos para visualizar las fracciones de superficie, temperatura global, poblaciones, biomasa, producción, y el ratio de producción sobre biomasa.
