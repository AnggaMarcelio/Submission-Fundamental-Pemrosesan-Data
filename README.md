# Submission-Fundamental-Pemrosesan-Data

## Struktur Proyek

```
.
├── main.py
├── tests/
│   ├── test_extract.py
│   ├── test_transform.py
│   └── test_load.py
├── utils/
│   ├── extract.py
│   ├── transform.py
│   └── load.py
├── products.csv
├── google-sheets-api.json
└── README.md
```

## Cara Menjalankan

### Jalankan Proses ETL
```bash
python main.py
````

### Jalankan Unit Test
```bash
python -m unittest discover tests
```

### Jalankan Test Coverage
```bash
coverage run -m unittest discover tests
coverage report -m
```
