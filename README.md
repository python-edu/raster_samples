# Image Processing Data

Images and raster data for Python exercises.

---

# Remote Sensing

- `remote_sensing/` — satellite images and aerial photographs from publicly available sources.

---

# Sample Images

- `sample_images/` — test images for display, histograms, contrast, filtering, and morphology.
- Source: [scikit-image sample data](https://scikit-image.org/docs/stable/api/skimage.data.html).
- **CC0 1.0:** `camera.png`, `cell.png`, `chelsea.png`, `gravel.png`, `horse.png` — [license](https://creativecommons.org/publicdomain/zero/1.0/).
- **Public domain:** `astronaut.png` (NASA photograph) — [source and copyright status](https://scikit-image.org/docs/stable/api/skimage.data.html#skimage.data.astronaut).
- **Allowed:** copy, modify, redistribute, and use commercially.
- **Attribution:** not required; citing the source is recommended.
- **Limitations:** provided without warranty; third-party privacy, publicity, or trademark rights may still apply.

---

# Download Images

1. **Selected images**
   - Open [`sample_images/`](sample_images/) on GitHub.
   - Select an image and click **Download raw file**.
   - Save it in `python_course/data/sample_images/`.

2. **Complete sample set**
   - Open [`sample_images.zip`](sample_images.zip) on GitHub and click **Download raw file**.
   - Save the ZIP in `python_course/`.
   - Extract it using the instructions below.

- GitHub **Code → Download ZIP** downloads the **entire repository**, not only `sample_images/`.

---

# Extract Sample Images

1. Open a terminal and go to `python_course/` (from its parent directory):

   ```bash
   cd python_course
   ```

2. Create `data/` if missing and `data/sample_images/` for the images.

3. Extract `sample_images.zip` into `data/sample_images/`.

   **Windows — PowerShell**

   Create the folders (if missing):

   ```powershell
   mkdir data
   mkdir data/sample_images
   ```

   If `mkdir` is not available, use:

   ```powershell
   New-Item -ItemType Directory -Force -Path data
   New-Item -ItemType Directory -Force -Path data/sample_images
   ```

   Extract the images:

   ```powershell
   Expand-Archive -Path sample_images.zip -DestinationPath data/sample_images
   ```

   **Linux / macOS**

   ```bash
   mkdir -p data/sample_images
   unzip sample_images.zip -d data/sample_images/
   ```

- Result: `python_course/data/sample_images/*.png`.
