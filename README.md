# 🐦 Detección de Pájaros con Visión Artificial  
| Video  |
|:---:|
| ![Demo principal](./video_2.gif) |

---
---

# 📌 Descripción del Proyecto

Este proyecto implementa un sistema de **detección automática de pájaros utilizando visión artificial y deep learning**.

El modelo fue entrenado para identificar aves en distintos entornos, incluyendo escenarios urbanos y naturales, logrando una detección robusta en tiempo real.

---

# 🧠 Entrenamiento del Modelo

- 🔍 Dataset: Imágenes de aves en múltiples condiciones (luz, fondo, distancia)  
- 🏋️ Entrenamiento: Realizado por **Junior Barrera**  
- ⚙️ Framework: YOLO / PyTorch  
- 🎯 Objetivo: Detección precisa y eficiente en tiempo real  
- 📈 Optimización: Ajuste de hiperparámetros y fine-tuning  

⚠️ **Nota:** Este modelo fue entrenado de manera personalizada.  
Si utilizas los pesos o este proyecto, por favor dar los créditos correspondientes.

---

# 📦 Pesos del Modelo

Los pesos entrenados están disponibles para su uso:

👉 `./weights/best.pt`

Puedes cargarlos directamente en tu implementación para realizar inferencia sin necesidad de reentrenar.

---

# 🎥 Resultados y Pruebas

Se incluyen videos de prueba procesados utilizando material de YouTube para validar el rendimiento del modelo.

📁 Carpeta de resultados:
👉 `./videos/`

Incluye:
- Detección en tiempo real  
- Diferentes escenarios  
- Pruebas de precisión del modelo  

---

# 🚀 Ejecución

```bash
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
pip install -r requirements.txt
python detect.py --weights weights/best.pt --source videos/test.mp4
