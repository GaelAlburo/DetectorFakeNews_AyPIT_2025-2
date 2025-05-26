
# Proyecto Final: Clasificación de Texto con Modelos Tradicionales y SaBERT

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-green)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red)
![Transformers](https://img.shields.io/badge/Transformers-4.0+-yellow)

## Descripción del Proyecto

Este proyecto implementa y compara diferentes modelos de clasificación de texto, incluyendo:

- Modelos tradicionales de Machine Learning (Random Forest, Naive Bayes, Regresión Logística)
- Modelo avanzado basado en transformers (SaBERT)

El código principal se encuentra en el Jupyter Notebook `proyectoFinal.ipynb` y utiliza datos almacenados en el directorio `data/`.

## Estructura del Proyecto

```
proyecto-final-nlp/
│
├── data/                     # Directorio de datasets
│   ├── onlyfakes1000.csv     # Únicamente noticias falsas
│   ├── onlytrue1000.csv      # Únicamente noticias verdaderas
│   └── test.cvs              # Noticias de prueba sin clasificar
│
│── proyectoFinal.ipynb       # Jupyter Notebook principal
│
│
├── README.md                 # Documentación
├── requirements.txt          # Dependencias
└── .gitignore                # Archivos ignorados por Git
```

## Requisitos

- Python 3.7 o superior
- Jupyter Notebook

### Dependencias

Instala las dependencias con:

```bash
pip install -r requirements.txt
```

O instálalas manualmente:

```bash
pip install pandas torch nltk scikit-learn transformers matplotlib seaborn tqdm ipykernel
```

## Uso

1. Clona este repositorio
2. Instala las dependencias como se indica arriba
3. Abre el notebook con Jupyter:

```bash
jupyter notebook proyectoFinal.ipynb
```

4. Ejecuta las celdas en orden

## Autores

* González Sotelo Elias Eduardo - 318023179
* González Villalba Bryan Jesús - 421530869

* Guzmán Alburo Rodrigo Gael - 318261896
* Ríos Nava Luis Eduardo - 421530924

* Rodríguez Ortiz Alexis Isaías - 318145994
