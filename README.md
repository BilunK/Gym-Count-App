# Gym Count

Estaba cansado de que en mitad de una serie, me quedara pensando "¿Esta es la segunda o tercera serie?", por eso hice esta App, para no tener que estar pensando en eso y centrarme en el ejercicio al completo, con esta aplicación podrás llevar el control de tus entrenamientos de gimnasio: planificas tu rutina de lunes a domingo, vas contando series durante el entreno, apuntas cómo te has sentido y sigues tu progreso. Todo es sencillo, rápido de usar con una mano y **se guarda solo en tu móvil**.

<img width="2180" height="1676" alt="Sin título" src="https://github.com/user-attachments/assets/eaae7371-7a3e-48b0-8dd3-c3ec10f511c4" />

## Qué aporta

- **Sin cuentas, sin internet, sin anuncios.** Todos los datos se quedan en tu teléfono.
- **Rutina semanal a tu medida.** Defines qué haces cada día, con cuántas series y repeticiones (o minutos).
- **Contador de series con un toque.** Círculos que se rellenan según avanzas; se ponen verdes al terminar el ejercicio.
- **Memoria de cómo te sientes.** Cierra cada día con un estado de ánimo y una nota opcional.
- **Marcas personales por ejercicio.** Guarda tu peso o tiempo y consulta cómo has mejorado.
- **Gráfica de progreso** para ver si llevas más días buenos que malos.
- **Copia de seguridad en .txt** para pasar tus datos a otro móvil.
- **Personalizable:** 8 colores, modo claro/oscuro, tamaño de letra y listas de músculos y unidades editables.
- **En tu idioma:** se adapta al del teléfono.

## Pestañas

La navegación está en el menú de las tres rayas (arriba a la izquierda). El engranaje (arriba a la derecha) abre los ajustes.

### Entrenamiento
- Muestra el día elegido con su fecha y día de la semana. Las flechas ‹ › o **deslizar el dedo** a izquierda y derecha cambian de día, y tocar la fecha vuelve a hoy.
- Cada ejercicio de tu rutina es una tarjeta con su nombre, el músculo y la cantidad (reps o min).
- Los **círculos son las series**. Con **+** cuentas una serie hecha y con **−** quitas la última.
- Si un ejercicio tiene varias filas (por ejemplo, 3 ejercicios de pecho), salen en la misma tarjeta, numeradas 1, 2, 3.
- Si dejas el nombre vacío en la rutina, se usa el nombre del músculo.
- El **lápiz** te lleva a editar la rutina de ese día.
- **Completar día:** un popup centrado te pide cómo te has sentido (*Horrible, Mal, Regular, Bien, Excelente*) y una nota opcional. Puedes cambiarlo o quitarlo después.
- **Los días completados quedan congelados:** se guardan los ejercicios que hiciste ese día y no les afectan los cambios posteriores de la rutina. Solo se pueden modificar si deshaces el día completado desde ese mismo día.

### Mi rutina
- Una pestaña por día, de lunes a domingo.
- Para cada ejercicio: nombre (opcional), músculo, número de ejercicios (1–10), series (1–20), cantidad (1–999) y unidad (*reps*, *min* o las que añadas).
- Los cambios se guardan al momento. También puedes cambiar de día deslizando a izquierda o derecha.

### Historial
- Lista de los días que has completado, del más reciente al más antiguo.
- Para cada día: cómo te sentiste, series hechas sobre el total, ejercicios realizados y tu nota si la escribiste.
- Tocar un día lo abre en Entrenamiento.

### Marcas
- Carpetas por músculo, que se deslizan con el dedo (en el mismo orden que tengas en los ajustes).
- Cada ejercicio guarda un **peso (kg)** o un **tiempo (min)**, y muestra tu marca actual comparada con la anterior (↑ ↓ =).
- Al tocar un ejercicio ves su **historial de marcas**, puedes añadir una nueva y borrar cualquiera individualmente.
- **Mantén pulsado** para seleccionar varios: puedes moverlos a otra carpeta o borrarlos con la papelera (con confirmación).
- Si borras un músculo, sus ejercicios pasan automáticamente a **Sin categoría**, una carpeta que solo aparece cuando tiene contenido.

### Progreso
- Una frase resumen ("Llevas más días bien que mal") y la tendencia de tus últimos días.
- Reparto de días buenos, regulares y malos, y media sobre 5.
- Gráfica de línea con los últimos 14 días completados.

### Ajustes
- **Apariencia:** sistema, claro u oscuro.
- **Color:** azul, morado, rosa, rojo, naranja, amarillo, verde o grafito.
- **Tamaño de letra:** cuatro pasos, con un límite máximo para que nada se descuadre.
- **Opciones avanzadas:**
  - Músculos: renombrar, añadir, borrar y reordenar. De base vienen pecho, espalda, pierna, hombro, bíceps, tríceps, core, glúteo, cardio, antebrazo y gemelo.
  - Unidades de medida: *reps* y *min* de base; puedes añadir, renombrar o borrar.
  - Exportar e importar una copia de todos tus datos en un archivo `.txt`.
  - Borrar todos los datos (botón rojo con doble confirmación) para dejar la app de fábrica.

## Idiomas

Español, inglés, francés, alemán, portugués e italiano. La app usa el idioma del teléfono; catalán, gallego y euskera se muestran en español, y cualquier otro idioma en inglés. Los textos de las funciones más recientes (Marcas, opciones avanzadas, notas, copia de seguridad) están traducidos al español y al inglés; en el resto de idiomas se muestran en inglés.

## Instalación

1. Entra en la sección **Releases** de este repositorio (barra lateral derecha) y descarga `Gym-Count.apk` desde el móvil.
2. Ábrelo. Android te pedirá permiso para instalar apps de fuera de la Play Store: acéptalo.
3. Si aparece un aviso de Play Protect, pulsa **Instalar de todos modos**.

**Al actualizar:** cada compilación se firma con una clave de depuración distinta, así que Android no deja instalar la nueva versión encima de la anterior. Antes de desinstalar, **exporta una copia** en *Ajustes → Opciones avanzadas* y después impórtala en la versión nueva.

## Privacidad y datos

- No hay servidores, cuentas ni análisis de uso. Nada sale de tu móvil.
- Los datos se guardan dentro de la app. Si la desinstalas o borras sus datos, se pierden; por eso existe la copia de seguridad en `.txt`.
- La copia incluye rutina, historial, marcas, músculos y unidades. **No incluye la apariencia** (color, modo claro/oscuro, tamaño de letra), que se queda como la tengas en cada móvil.
- El guardado es compacto: fechas como números, ejercicios repetidos guardados una sola vez y datos en listas sin nombres de campo. Ocupa unos 20 KB por cada año de entrenamiento (en torno a 90 bytes por día), así que años de historial caben de sobra.

## Cómo está hecha

- Toda la app es un único archivo, `www/index.html`, en HTML, CSS y JavaScript sin librerías.
- Se empaqueta como app de Android con [Capacitor](https://capacitorjs.com/) 8 (plugins *Filesystem* y *Share* para exportar la copia).
- La compilación del APK se hace en la nube con GitHub Actions (Node 22 y Java 21) y se publica en *Releases*.

```
.
├── www/index.html                 La app completa
├── icono/res/                     Iconos de Android
├── capacitor.config.json          Configuración de Capacitor
├── package.json                   Dependencias
└── .github/workflows/android.yml  Compilación automática del APK
```

Hecho por **Miguel Palarea García**
