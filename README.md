# Modelo Universal Superfluido (MUS-AG) - Repositorio Oficial

Repositorio oficial de la arquitectura computacional y algorítmica del **Modelo Universal Superfluido (MUS-AG)**, una meta-teoría que sustituye el espacio-tiempo elástico y el "vacío pasivo" por la dinámica de fluidos incompresibles sobre un sustrato de Pre-materia operando a 2.7K.

Este repositorio contiene los motores de simulación en Python que demuestran empírica y computacionalmente la falsabilidad del modelo, resolviendo la divergencia caótica del problema de los N-Cuerpos y la precesión secular de Mercurio sin recurrir a tensores relativistas.

## 📚 Documentación Teórica y Publicación
El soporte teórico, la epistemología (Teoría de Teorías) y la justificación hidrodinámica completa de las constantes (Fórmula Magna) se encuentran protegidos y publicados bajo el siguiente DOI en Zenodo:

*   **DOI:** 10.5281/zenodo.22984090
*   **Autor Intelectual:** Ricardo Andrés Araya Soza

## ⚙️ Motores Computacionales Incluidos

Este repositorio contiene cinco (5) scripts fundamentales:

### 1. Motores de Resolución Astrofísica
*   **`Motor_MUS-AG_V3.6_NCuerpos.py`**: Simulador determinista del Sistema Solar. Demuestra la resolución del caos de N-Cuerpos al erradicar la tracción mutua, operando mediante flotabilidad isobárica pasiva (Navegación por Gradientes).
*   **`Motor_V5.1_OmniTopologico.py`**: Simulador de campos fuertes. Absorbe la precesión relativista de Mercurio aplicando la compresión convectiva de Bernoulli y detecta el arrastre de fricción en la Capa Límite (roce acústico) sin tensores PPN.

⚠️ Nota Epistemológica y de Homologación Conceptual (Euler vs. Prandtl)
El Modelo MUS-AG y sus motores operan matemáticamente bajo el límite estricto de Euler (μ = 0), demostrando computacionalmente que la Pre-materia está exenta de disipación térmica (viscosidad clásica).Los términos 'Capa Límite' y 'Fricción Acústica' (mencionados en el Motor V5.1 y en la documentación teórica) son utilizados transitoriamente como puentes semánticos para homologar la didáctica de la astrofísica ortodoxa. Estructuralmente, la 'Capa Límite' representa una Zona de Confinamiento Acústico Externo (interferencia constructiva de presión) y la 'Fricción' reportada es puramente un Arrastre por Dispersión de Ondas de Presión (Wave Drag), operando sin pérdida entrópica en el ecosistema a 2.7K.

### 2. Scripts de Comprobación Teórica
*   **`Comprobacion_Postulados.py`**: Script de auditoría dimensional. Demuestra computacionalmente la derivación de la Presión Absoluta del universo y la invarianza de c bajo la Ecuación de Newton-Laplace.
*   **`Codigo_ToE_Mejorado.py`**: Algoritmo de la Fórmula Magna. Unifica la Gravedad, el Electromagnetismo y las Fuerzas Nucleares bajo el empuje hidrostático y el Efecto Venturi femtométrico.
*   **`Comprobacion_N_Cuerpos.py`**: Renderizador interactivo (Plotly) que visualiza las isóbaras, los Puntos Muertos Hidrostáticos y la navegación pasiva de los astros a través de los gradientes de presión generados por los macro-sumideros.

## 🛠️ Instalación y Dependencias

Para auditar y ejecutar estos motores localmente, se requiere Python 3.8+ y las siguientes librerías de cálculo científico:

```bash
pip install numpy scipy plotly matplotlib
```

## 🚀 Ejecución

Para correr cualquier simulación, ejecute el script directamente desde su terminal o IDE:

```bash
python Motor_MUS-AG_V3.6_NCuerpos.py
```
> *Nota: Las integraciones de alta precisión (DOP853) para periodos de tiempo extensos pueden requerir algunos segundos de procesamiento.*

## ⚖️ Declaración de Derechos de Autor y Uso
**Aviso de Propiedad Intelectual:** La presente arquitectura algorítmica, las fórmulas de conversión fluida y los códigos ejecutables adjuntos son propiedad exclusiva de **Ricardo Andrés Araya Soza**. 
Todos los derechos reservados bajo las leyes de propiedad intelectual internacionales y el Convenio de Berna. Queda estrictamente prohibida su reproducción no autorizada, adaptación, distribución o explotación comercial sin autorización previa y por escrito del titular. Este repositorio se hace público con fines estrictamente académicos, de auditoría científica y comprobación de falsabilidad.
