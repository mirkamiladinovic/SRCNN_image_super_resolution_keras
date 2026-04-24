### 📦 SRCNN Image Super Resolution (Keras - Jupyter Notebook Version)

Ovaj repozitorijum sadrži implementaciju Super-Resolution Convolutional Neural Network (SRCNN) modela koristeći Keras biblioteke, predstavljen kroz Jupyter Notebook.

#### 📁 Sadržaj

- `srcnn_demo.ipynb`: Glavni notebook koji demonstrira:
  - učitavanje niskorezolutnih slika,
  - pripremu podataka za treniranje,
  - evaluaciju rezultata kroz PSNR metriku i vizuelizaciju.

#### 🧐 Model

SRCNN je jednostavan konvolucioni neuronski model dizajniran za povećanje rezolucije slika. Radi tako što „rekonstruiše“ visokorezolutne slike iz njihovih niskorezolutnih verzija.

#### ⚙️ Zahtjevi

- Python 3.x
- Keras
- TensorFlow (kao backend)
- OpenCV
- NumPy
- Matplotlib

Instalacija zahtjeva:

```bash
pip install -r requirements.txt
```

#### ▶️ Pokretanje

Notebook možete otvoriti u Google colabu ili pokrenuti lokalno:

```bash
jupyter notebook srcnn_demo.ipynb
```
