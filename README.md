<div align="center">

  <h1>OnGi</h1>
  <p><strong>Record Our Cultural Heritage, Bring It Back in 3D</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
    <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  </p>
</div>

---

## About

Korea is home to thousands of cultural artifacts — ancient Buddhist statues, royal relics, and excavated treasures that carry centuries of history. Yet many of them remain fragile, undocumented, and at risk of being lost forever.

OnGi is a crowdsourced cultural heritage preservation platform inspired by the idea that everyday people, armed with nothing more than a smartphone camera, can collectively help protect and restore history. When users visit a museum, a temple, or a historic site, they photograph the artifacts they encounter and upload them to the app. These photos are tagged, accumulated, and when enough images of the same artifact are gathered, a 3D model is reconstructed using photogrammetry — turning a crowd of ordinary snapshots into a digital preservation of a national treasure.

The more people contribute, the richer and more accurate the archive becomes. OnGi turns every visitor into a guardian of Korean cultural heritage.

---

## How It Works

<div align="center">
  <img src="assets/workflow.png" width="700"/>
</div>

<br/>

### 1. Capture & Upload
Users visit museums, temples, and historic sites and photograph the artifacts they encounter. Each photo is uploaded to the app and tagged with the artifact name.

### 2. Crowdsource & Accumulate
Photos from different users of the same artifact are automatically grouped. Once 10 or more images are collected, the artifact entry is created in the system.

### 3. Review & Verify
Admins review the accumulated images, verify the artifact information, and prepare the dataset for 3D reconstruction.

### 4. Reconstruct in 3D
The verified image set is processed through photogrammetry software, transforming hundreds of ordinary photos into a detailed 3D model.

### 5. Explore & Preserve
The 3D model is published in the app for anyone to explore. Users can browse the artifact from every angle, read its history, and see the community feeds that made it possible — while the artifact is digitally preserved for future generations.

<div align="center">
  <img src="assets/artifact_screens.png" width="700"/>
</div>

---

## Tech Stack

| | Technology |
|---|---|
| **Frontend** | Flutter |
| **Backend** | Django REST Framework |
| **Database** | PostgreSQL |
| **Admin** | Django Admin |
| **State Management** | Provider |

---

## Getting Started

### Requirements
- Flutter SDK 3.6.1
- Python 3.11.5
- PostgreSQL

### Backend
```bash
cd OnGi_api
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend
```bash
cd OnGi_flutter
flutter pub get
flutter run
```

---

## Developer

**Jihun Cho**
- GitHub: [@Jihun37](https://github.com/Jihun37)
