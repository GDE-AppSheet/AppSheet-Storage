
# 📂 Plantilla AppSheet + Google Drive
<img width="1291" height="439" alt="Logo-ESC-2020-hor2" src="https://github.com/user-attachments/assets/cf53bddf-1cce-464f-a251-c36fb72ac571" />

Este repositorio contiene la documentación y archivos de ejemplo para crear una app en **AppSheet** que maneja documentos de **Google Drive** de forma segura, sin exponer datos corporativos.

🔗 **Demo en GitHub Pages:**  
[https://<tu-usuario>.github.io/appsheet-drive-template](https://<tu-usuario>.github.io/appsheet-drive-template)

---

## 📚 Documentación por módulos

- [Módulo 1: Catálogo de documentos con Google Sheets](docs/modulo-1-catalogo-sheets.md)  
- [Módulo 2: Conexión oficial de AppSheet a carpetas de Drive](docs/modulo-2-drive-folder.md)  
- [Módulo 3: Crear carpetas en Drive con Apps Script](docs/modulo-3-appscript-carpetas.md)  
- [Checklist de saneamiento](docs/checklist-saneamiento.md)  
- [Guía: publicar en GitHub Pages](docs/gh-pages-setup.md)

---

## 📂 Archivos incluidos

- `sample-data/Documentos-demo.csv`: dataset de ejemplo con nombres, URLs y metadatos ficticios.  
- `assets/screenshots/`: carpeta para guardar capturas genéricas (sin IDs sensibles).  
- `docs/`: toda la documentación paso a paso.  

---

## 🚀 Cómo usar esta plantilla

1. **Clona** o descarga este repositorio.  
2. En AppSheet:
   - Crea una copia de tu app original.  
   - Sustituye fuentes de datos por la hoja de ejemplo o AppSheet Database.  
   - Conecta la tabla `Documentos-demo.csv` (o su equivalente en GSheet).  
3. Sigue los módulos paso a paso según lo que quieras demostrar.  
4. Publica tu app como **sample/template** y activa “Allow users to copy your app”.  
5. Agrega en `index.md` el enlace directo a la plantilla AppSheet para que cualquiera la copie.  

---

## ✅ Checklist rápido

Antes de compartir tu plantilla, asegúrate de:

- [ ] Ninguna tabla apunta a carpetas corporativas.  
- [ ] Todos los IDs están en **Script Properties**, no hardcodeados.  
- [ ] Archivos de ejemplo en `sample-data/`, no reales.  
- [ ] Logos/imágenes genéricas (no corporativos).  
- [ ] Bots/Tasks sensibles eliminados o con mocks.  
- [ ] Filtros de seguridad aplicados (ej: `[OwnerEmail]=USEREMAIL()`).  
- [ ] App publicada como **Sample/Template** y con **Allow copy** activo.  

---
