# 🖼️ Image & Metadata OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| ExifTool | Extract metadata from images and files | [exiftool.org](https://exiftool.org) |
| Jeffrey's Exif Viewer | Online EXIF metadata viewer | [exifdata.com](https://www.exifdata.com) |
| Google Lens | Reverse image search and object recognition | [lens.google.com](https://lens.google.com) |
| Yandex Images | Reverse image search (strong for faces) | [yandex.com/images](https://yandex.com/images) |
| TinEye | Reverse image search and tracking | [tineye.com](https://tineye.com) |
| FotoForensics | Image authenticity and manipulation analysis | [fotoforensics.com](https://fotoforensics.com) |
| Forensically | Error level analysis and clone detection | [29a.ch/photo-forensics](https://29a.ch/photo-forensics) |
| Deepware Scanner | Deepfake detection | [deepware.ai](https://deepware.ai) |
| Sensity | AI-generated and deepfake image detection | [sensity.ai](https://sensity.ai) |
| GeoSpy | AI-based image geolocation | [geospy.ai](https://geospy.ai) |
| PimEyes | Face recognition reverse search | [pimeyes.com](https://pimeyes.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Extract metadata with ExifTool — look for GPS, device, timestamp
2. Run reverse image search (Google Lens, Yandex, TinEye) to find original source
3. Analyze image authenticity (FotoForensics, Forensically) for signs of manipulation
4. Check for deepfake indicators (Deepware, Sensity)
5. Use GeoSpy or SunCalc for geolocation if no GPS metadata
6. Cross-reference findings with other collected data
7. Archive the original image immediately

**FR**
1. Extraire les métadonnées avec ExifTool — chercher GPS, appareil, horodatage
2. Lancer une recherche inversée (Google Lens, Yandex, TinEye) pour trouver la source originale
3. Analyser l'authenticité de l'image (FotoForensics, Forensically) pour détecter des manipulations
4. Vérifier les indicateurs de deepfake (Deepware, Sensity)
5. Utiliser GeoSpy ou SunCalc pour la géolocalisation si pas de métadonnées GPS
6. Recouper les résultats avec les autres données collectées
7. Archiver l'image originale immédiatement

---

## 💡 Tips & Good Practices / Conseils

- Most social media platforms strip EXIF data on upload — but messaging apps often don't
- Yandex is significantly better than Google for face-based reverse image search
- Error Level Analysis (ELA) highlights areas of an image that have been edited
- AI-generated images often have telltale signs — unnatural hands, asymmetric features, background inconsistencies
- Always work on a copy of the original image — never alter the evidence
- Screenshot metadata is different from photo metadata — know the difference

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| GPS coordinates embedded in image | Location disclosure |
| Image found on multiple unrelated sites | Stolen or reused identity photo |
| ELA shows heavy editing in specific areas | Image manipulation |
| Deepfake score above threshold | Synthetic media |
| Timestamp inconsistency | Metadata manipulation |

---

## 🔗 Useful Resources / Ressources utiles

- [ExifTool Documentation](https://exiftool.org)
- [FotoForensics](https://fotoforensics.com)
- [Bellingcat — Reverse Image Search Guide](https://www.bellingcat.com)
- [Deepware Scanner](https://deepware.ai)
