
En esta carpeta se encuentran bases de datos dónde se pueden poner en práctica las visualizaciones vistas en clase.

## Descripción de las bases de datos presentes:

### **credit_risk_dataset.csv**

Base de datos para estudiar el riesgo de incumplimiento crediticio, es decir, de la posibilidad de que las empresas/individuos no puedan realizar los pagos requeridos de sus obligaciones de deuda. 
Las variables presentes son:

- person_age: Edad.
- person_income: ingresos anuales.
- personhomeownership: Propiedad de la vivienda (dueño, alquila, etc.).
- personemplength: Duración del empleo (en años).
- loan_intent: Intención del préstamo.
- loan_grade: Grado del préstamo.
- loan_amnt: Cantidad del préstamo.
- loanintrate: Tasa de interés.
- loan_status: Estado del préstamo (1 es default, 0 es no default).
- loanpercentincome: Porcentaje del préstamo respecto de los ingresos.
- cbpersondefaultonfile: Historia de default (Sí o no).
- cbpersoncredhistlength: Duración del historial de créditos.  

Pueden ver más información en la competencia de [Kaggle](https://www.kaggle.com/datasets/laotse/credit-risk-dataset).

### **BDs_empleo_impo.csv**

Se dispone de datos de importaciones de productos de las empresas argentinas para el año 2017 desde las distintas aduanas. Puede ser utilizada para analizar el posible agrupamiento en alguna de las siguientes dimensiones: i) por tipo de actividad ii) por tipo de producto iii) país procedencia iv) aduana v) medio de transporte vi) destino nacional.

Las variables incluidas en la base son:
 
- Estado: estado de la mercadería
- Año: año de información 
- medio_tra: medio de transporte utilizado
- umed_decl: unidad de medida declarada
- umed_estad: unidad de medida estadarizada
- aduana: aduana por la que ingresa la mercadería
- procedenc: país de la mercadería
- destinac: destino que se le da a la mercadería en el país
- mes: mes de la importación de la mercadería
- posic_sim: posición arancelaria de la mercadería (revisar nomenclatura)
- cant_decl: cantidad de mercadería en la unidad declarada
- cant_unest: cantidad en unidades estandarizada
- fob: precio FOB
- kilos: peso de la mercadería en kilos
- cif: precio CIF
- id: identificador de la empresa importadora anonimizada

### **SP500 oil gold bitcoin.csv**

La base de datos contiene información sobre diferentes activos, a fin de estudiar su comportamiento.

Se puede trabajar con los precios en USD, pero lo común en finanzas es trabajar con los RETORNOS de los activos  donde Rt es el retorno del activo en t, Pt el precio del activo en t y Pt-1 el precio del activo en t-1.

Las variables incluidas en la base son el precio en dólares de los diferentes activos.