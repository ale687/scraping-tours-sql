# Tour Scraper with Email Alerts

Este proyecto realiza **web scraping** de una página de eventos musicales y envía una notificación por correo electrónico si se detecta un nuevo evento. Los datos se almacenan en una **base de datos SQLite** para evitar duplicados.

---

## 🛠️ Tecnologías utilizadas

- `requests`: para hacer solicitudes HTTP
- `selectorlib`: para extraer información del HTML mediante selectores definidos en `extract.yaml`
- `sqlite3`: para guardar eventos en una base de datos local
- `smtplib` y `ssl`: para enviar correos electrónicos
- `python-dotenv`: para cargar credenciales desde un archivo `.env`

---

## ⚙️ Cómo usar

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/tour-scraper.git
   cd tour-scraper
