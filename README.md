# Variabilidad_de_la_Frecuencia_Cardiaca_-HRV-
Este laboratorio trata el análisis digital de un electrocardiograma real para examinar la variabilidad en el ritmo cardíaco. Se lleva a cabo una segmentación en el tiempo, identificación automática de los picos R, cálculo de los intervalos RR y elaboración de gráficos de Poincaré.

## Parte A
### Actividad Simpatica y Parasimpatica con sus efectos en el sistema cardiaco
El sistema simpático y el sistema parasimpático son dos divisiones del sistema nervioso autónomo que actúan de manera contraria para mantener el equilibrio en el cuerpo. El sistema simpático se activa en situaciones de "lucha o huida", preparando al organismo para el estrés con reacciones como el incremento de la frecuencia cardíaca y la dilatación de las pupilas. En contraste, el sistema parasimpático fomenta la tranquilidad y la recuperación, gestionando procesos como la digestión, disminuyendo la frecuencia cardíaca y contrayendo las pupilas.

Sistema simpático ("lucha o huida")
Función: Se encarga de preparar el cuerpo para reaccionar rápidamente frente a un peligro o reto, movilizando energía.
Efectos:
Eleva la frecuencia cardíaca y la intensidad de contracción.
Dilata las pupilas.
Incrementa la presión arterial.
Estimula la liberación de adrenalina.
Reduce la actividad digestiva.

Sistema parasimpático ("descanso y digestión")
Función: Predomina en momentos de tranquilidad, conservando energía y favoreciendo procesos de restauración.
Efectos:
Reduce la frecuencia cardíaca.
Constriñe las pupilas.
Fomenta la digestión al incrementar la actividad intestinal y la producción de saliva y jugos gástricos.
Relaja los músculos de las vías respiratorias.
Facilita la micción y la evacuación.

Cómo trabajan juntos, ambos sistemas funcionan continuamente en un estado de equilibrio conocido como tono simpático y tono parasimpático.
El sistema nervioso simpático se activa en situaciones de riesgo, mientras que el parasimpático actúa para restablecer la normalidad una vez que el peligro ha desaparecido.
Esta interacción opuesta y equilibrada es fundamental para el bienestar general y la supervivencia del ser vivo.

### Variabilidad de la frecuencia cardíaca (HRV)
La variabilidad de la frecuencia cardíaca (HRV) se determina mediante la señal del electrocardiograma (ECG), al analizar las diferencias temporales entre latidos sucesivos (intervalos R-R). Este examen brinda información significativa sobre el estado cardiovascular, los niveles de estrés y la capacidad del organismo para ajustarse a diferentes situaciones. Una HRV elevada generalmente sugiere una mejor salud y recuperación, mientras que una HRV baja podría estar relacionada con estrés, mala calidad del sueño o problemas de salud que hay que investigar.

¿Cómo se mide la HRV a partir del ECG?
Identificación de picos R: Se localizan y etiquetan los picos R consecutivos en la señal de ECG, los cuales representan la despolarización de los ventrículos.
Cálculo de intervalos R-R: Se estima el tiempo que transcurre entre cada conjunto de picos R contiguos.
Análisis de la variabilidad: Se examinan las variaciones en estos intervalos R-R para determinar la HRV.

Métodos de análisis
Métodos en el dominio del tiempo: Son los más básicos y se enfocan en estudiar los intervalos R-R para calcular variables como el intervalo medio NN, la frecuencia cardíaca promedio y la diferencia entre los intervalos más largos y más cortos.
Métodos en el dominio de la frecuencia: Analizan la señal de la HRV en términos de sus frecuencias individuales.
Métodos no lineales: Proporcionan información adicional y son útiles para evaluar el impacto de hormonas y temperatura, aunque su uso es menos común debido a su complejidad.

Qué revela la HRV
Alta HRV: Se vincula con una buena condición física, mejor adaptación al estrés, adecuada recuperación y un estado mental positivo.
Baja HRV: Puede ser un signo de estrés, mala calidad del sueño, exceso de entrenamiento o problemas de salud más graves, como hipertensión y enfermedades cardíacas.

### Diagrama de Poincaré como herramienta de análisis
La Variabilidad de la Frecuencia Cardíaca (VFC o HRV) se refiere a los cambios en el tiempo entre los latidos del corazón, y se origina a partir de la interacción de varios osciladores fisiológicos que regulan la actividad del nódulo sinusal. Por esta razón, el estudio de la VFC facilita la evaluación no invasiva del sistema nervioso autónomo, así como la capacidad del corazón para adaptarse a diferentes exigencias fisiológicas.

El análisis que se presenta en este informe utiliza el diagrama de Poincaré como método para examinar la serie R-R, con el propósito de evaluar un enfoque cuantitativo para el estudio de la VFC. A pesar de que su utilidad cualitativa está bien establecida, el uso cuantitativo aún necesita estandarización, especialmente en lo que respecta a la definición de índices y su interpretación fisiológica.

Se llevaron a cabo registros de ECG durante 10 minutos en un grupo de 15 pacientes con VFC reducida (diabetes tipo 1 de larga duración) y un grupo control de 15 personas de edad comparable (42–70 años). A partir de estas grabaciones, se recuperaron los intervalos RR, y se calcularon tanto índices tradicionales de VFC (estadísticos y espectrales) como parámetros obtenidos de los diagramas de Poincaré.

En lugar de utilizar el Poincaré de manera convencional (retardo 1), se generaron diagramas con diferentes retardos (2, 3, 5, 6, 7, 10 y 20), ajustando elipses a cada conjunto de puntos. De estas elipses se derivaron tres índices cuantitativos: área, diámetro mayor (Dmax) y diámetro menor (dmin), cada uno identificado con su respectivo retardo.

Los resultados indicaron que los índices obtenidos del diagrama de Poincaré fueron tan eficaces como los convencionales para diferenciar entre los pacientes con VFC reducida y el grupo de control (p 0. 96). Además, dmin1 mostró una fuerte correlación con índices de variabilidad a corto plazo (RMSSD y HF), los cuales están estrechamente relacionados con la actividad del sistema parasimpático (r ≥ 0. 95).

En los pacientes diabéticos, dmin20 se asoció tanto con RMSSD y HF como con SDNN (r = 0. 92), mientras que en el grupo control, este índice presentó la correlación más significativa con la banda LF, la cual está vinculada a la acción conjunta de los sistemas simpático y parasimpático. Esta diferencia en el comportamiento resalta la utilidad del análisis de Poincaré para identificar alteraciones autonómicas específicas, como las que resultan de la neuropatía diabética.

En resumen, el estudio evidencia que el diagrama de Poincaré no solo representa una herramienta visual eficaz, sino que también constituye una técnica cuantitativa robusta para el análisis de la VFC y el equilibrio autonómico. Su capacidad para diferenciar entre diversos estados autonómicos y superar las limitaciones de los métodos convencionales lo convierte en un recurso valioso para investigaciones y aplicaciones clínicas. En este informe, el estudio será utilizado como referencia y guía para contextualizar el análisis de la serie R-R y entender el papel del Poincaré en la evaluación del equilibrio entre los sistemas simpático y parasimpático.


## Parte B

Se muestra a continuacion el diagrama de flujo de respectiva para esta parte:


Antes que todo se llamaron las bibliotecas que se utilizaran principalmente en este laboratorio y su buen analisis de este.
``` python
import numpy as np
import matplotlib.pyplot as plt
!pip install wfdb   #Instalacion en colab
import wfdb
import pandas as pd
```
Este código analiza una señal de electrocardiograma (ECG) que se obtuvo directamente de un sujeto durante la sesión en el laboratorio. La grabación tuvo una duración total de 4 minutos (240 segundos), que se dividieron en dos fases: 2 minutos en completo reposo y 2 minutos realizando una lectura en voz alta, con el objetivo de provocar alteraciones fisiológicas en la frecuencia del pulso y observar su respuesta dinámica.
Para asegurar la correcta captura de la actividad eléctrica del corazón, se utilizó una tasa de muestreo de 2000 Hz, elegida conforme al principio de Nyquist, que indica que la tasa de muestreo debe ser al menos el doble de la frecuencia máxima presente en la señal. Dado que las partes relevantes del ECG están por debajo de 250 Hz (que es el nivel base del sistema utilizado), se eligió una frecuencia que es cuatro veces este valor, garantizando así una reconstrucción precisa y evitando la pérdida de información detallada del complejo QRS.
A partir de esta tasa de muestreo, se elaboró el vector de tiempo correspondiente, lo cual permite mostrar adecuadamente el desarrollo de la señal a lo largo de los 240 segundos completos. Finalmente, utilizando Matplotlib, se graficó la señal capturada, ilustrando claramente las diferencias entre el estado de reposo y la lectura en voz alta, y facilitando la identificación de los cambios en la actividad eléctrica del corazón a lo largo de toda la adquisición.

``` python
datos = np.loadtxt('/content/drive/MyDrive/Senal_lab_corazon.10.txt')
print("Dimensiones del archivo:", datos.shape)

# columnas → tiempo y señal
if datos.shape[1] == 2:
    tiempo = datos[:,0]
    senal = datos[:,1]
else:
    # Si solo hay una columna, el tiempo se genera artificialmente
    senal = datos
    fs = 2000 # frecuencia de muestreo (ajusta)
    tiempo = np.arange(len(senal)) / fs

fs = 2000
duracion_deseada = 240
muestras = int(duracion_deseada * fs)

plt.figure(figsize=(10,4))
plt.plot(tiempo[:muestras], senal[:muestras], color='orange')
plt.title('Señal EMG real ')
plt.xlabel('Tiempo [s]')
plt.xlim(0,240)
plt.ylim(0,5)
plt.ylabel('Voltaje [mV]')
plt.grid(True)
plt.show()
```
<img width="833" height="393" alt="image" src="https://github.com/user-attachments/assets/6dbcfacb-4d74-4fbf-86e6-ff350c4289c4" />

## Parte C
Se muestra a continuacion el diagrama de flujo de respectiva para esta parte B y la realizacion del filtro IIR:

Para analizar la señal de ECG obtenida en el laboratorio, se requirió establecer un filtro digital IIR (Respuesta a Impulso Infinito) para suprimir elementos no deseados y mantener solo la información fisiológica importante. Dado que el ECG es muy susceptible a diversos tipos de ruidos, seleccionar correctamente las frecuencias de corte y el tipo de filtro afecta de manera directa la calidad del análisis posterior (determinación de picos R, cálculo de intervalos RR y HRV).

El rango operativo de un electrocardiograma estándar se establece entre 0. 5 Hz y 40 Hz:
- 0. 5 Hz → Es la frecuencia más baja que refleja el movimiento lento del complejo P-QRS-T. Por debajo de este umbral, se presenta el ruido de la línea base derivado de la respiración, el movimiento corporal, variaciones en el contacto de los electrodos o la sudoración.
- 40 Hz → Es el límite superior para el contenido espectral significativo del electrocardiograma. Superando este valor, se presentan ruidos como:
Ruido muscular (EMG)
Artefactos por movimientos
Ruidos de alta frecuencia del sistema
Interferencias digitales

Por otra parte el filtro IIR se sellecciono por sus beneficios prácticos en sistemas biomédicos de recolección de señales:
- Alta eficiencia:
Con un número reducido de coeficientes, logra pendientes pronunciadas, lo que posibilita la obtención de una banda de rechazo estrecha sin tener que recurrir a órdenes elevados, como sucedería con un FIR.
- Mejor aprovechamiento de recursos:
Al captar señales durante períodos prolongados (240 segundos), un IIR disminuye considerablemente el tiempo de procesamiento y el consumo de memoria.
- Alta capacidad de selectividad:
Facilita la atención de las necesidades del ECG, donde es necesario:
Atenuar de manera efectiva la deriva de baja frecuencia.
