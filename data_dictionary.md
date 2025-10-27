# Data Dictionary - Heart Disease (Cleveland processed)

"
| Columna | Descripción |
|---|---|
| age | Edad del paciente (años) |
| sex | Sexo (1 = masculino, 0 = femenino) |
| cp | Tipo de dolor en el pecho (1-4) |
| trestbps | Presión arterial en reposo (mm Hg) |
| chol | Colesterol sérico (mg/dl) |
| fbs | Azúcar en sangre en ayunas > 120 mg/dl (1 = true; 0 = false) |
| restecg | Resultados del electrocardiograma en reposo (0,1,2) |
| thalach | Frecuencia cardiaca máxima alcanzada |
| exang | Angina inducida por ejercicio (1 = yes; 0 = no) |
| oldpeak | Depresión ST inducida por ejercicio respecto al reposo |
| slope | Pendiente del segmento ST del ejercicio |
| ca | Número de vasos principales (0-3) coloreados por fluoroscopia |
| thal | 3 = normal; 6 = defecto fijo; 7 = defecto reversible |
| target | Presencia de enfermedad cardíaca (1 = enfermedad, 0 = no) |

Nota: en el dataset original `target` toma valores 0 (no) y 1-4 (varios grados).
En este análisis se transformó a binaria: 0 = no enfermedad, 1 = enfermedad.
