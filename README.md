
---

## 📈 Ejemplos de Gráficos e Insights Obtenidos

### 🔸 Distribución de Evasión (`distribucion_churn.png`)
![Distribución de Evasión](images/distribucion_churn.png)  
El 26.6% de los clientes abandonaron el servicio. Esta tasa de evasión es considerable y merece atención estratégica.

---

### 🔸 Correlación entre Variables (`correlacion_variables.png`)
![Correlación](images/correlacion_variables.png)  
Se observa una alta correlación positiva entre la evasión y factores como:
- **Meses como cliente (tenure)**: los clientes nuevos tienden a abandonar más rápido.
- **Ingresos mensuales bajos** también se asocian con mayor evasión.
- Contratos mensuales tienen mayor probabilidad de evasión frente a contratos anuales.

---

### 🔸 Ingresos Mensuales vs Churn (`ingresos_vs_churn.png`)
![Ingresos](images/ingresos_vs_churn.png)  
Los clientes con ingresos mensuales bajos son más propensos a cancelar el servicio.

---

### 🔸 Tipo de Contrato vs Churn (`contratos_vs_churn.png`)
![Contrato](images/contratos_vs_churn.png)  
Los contratos de tipo "Mes a Mes" tienen la mayor tasa de cancelación, mientras que los contratos a largo plazo retienen mejor a los clientes.

---

### 🔸 Número de Servicios Contratados (`servicios_vs_churn.png`)
![Servicios](images/servicios_vs_churn.png)  
Cuantos más servicios tiene un cliente, menor es su probabilidad de evasión. Ofrecer paquetes integrados puede ser una buena estrategia de retención.

---

## 🧪 Cómo Ejecutar el Notebook

1. Asegúrate de tener Python 3.8+ y Jupyter Notebook instalado.
2. Clona este repositorio o descarga los archivos.
3. Instala las dependencias necesarias:
   ```bash
   pip install pandas matplotlib seaborn
