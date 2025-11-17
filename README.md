# School,Faculty,Deparment JSON Dataset

Bu proje, **okul, fakülte, bölüm** verilerini JSON formatında sağlar. Veriler **relational-style** (ilişkisel) olarak düzenlenmiştir ve projelerde okul/fakülte/bölüm ilişkilerini yönetmek için kullanılabilir.

---

## JSON Yapısı

### 1. Schools (Okullar(Üniversiteler))

```json
[
  {
    "schoolId": "100",
    "schoolName": "ABANT İZZET BAYSAL ÜNİVERSİTESİ"
  }
]
```

### 2.Faculty (Fakülteler)

```json
[
  {
    "facultyId": "300",
    "facultyName": "GEREDE MESLEK YÜKSEKOKULU",
    "schoolId": "100"
  },
  {
    "facultyId": "301",
    "facultyName": "BEDEN EĞİTİMİ VE SPOR YÜKSEKOKULU",
    "schoolId": "100"
  },
  {
    "facultyId": "302",
    "facultyName": "BOLU MESLEK YÜKSEKOKULU",
    "schoolId": "100"
  }
]
```

### 3.Department (Bölümler)

```json
[
  {
    "departmentId": "400",
    "schoolId": "100",
    "departmentName": "ULAŞTIRMA HİZMETLERİ BÖLÜMÜ",
    "facultyId": "300"
  },
  {
    "departmentId": "401",
    "schoolId": "100",
    "departmentName": "ANTRENÖRLÜK EĞİTİMİ BÖLÜMÜ",
    "facultyId": "301"
  },
  {
    "departmentId": "402",
    "schoolId": "100",
    "departmentName": "BEDEN EĞİTİMİ VE SPOR BÖLÜMÜ",
    "facultyId": "301"
  },
]
```