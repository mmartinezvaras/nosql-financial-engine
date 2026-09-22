# Motor NoSQL Financiero en la Nube (MongoDB Atlas & PyMongo)

## 📌 Descripción del Proyecto
Pipeline de almacenamiento, filtrado y análisis NoSQL enfocado en el sector bancario. Utiliza **MongoDB Atlas** alojado en la nube e integrado con **Python (`pymongo`)** para la gestión de cuentas de clientes, procesamiento de transacciones y cálculo de métricas financieras[cite: 1].

---

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías:** `pymongo`, `dnspython`
* **Base de Datos NoSQL:** MongoDB Atlas (AWS Cloud Sandbox)
* **Entorno de Ejecución:** Google Colab

---

## 📊 Funcionalidades y Consultas
1. **Modelado NoSQL:** Documentos JSON flexibles con información de saldos y tipos de cuentas[cite: 1, 2].
2. **Consultas y Filtros:** Búsquedas por rangos de saldo (`$gt`), creación e inspección de índices simples y compuestos[cite: 1, 2].
3. **Framework de Agregaciones (`aggregate`):** Pipeline multi-etapa (`$match`, `$group`, `$sort`, `$avg`) para obtener saldos medios e indicadores financieros[cite: 1, 2].
4. **Modelado Avanzado:** Documentos embebidos (notación de punto) y manipulación de listas de transacciones (`$push`)[cite: 1, 2].
