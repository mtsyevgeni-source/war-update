# מפת עדכונים – Ukraine War Updates

זהו פרויקט שמציג מפה חיה עם עדכוני חזיתות, מבוסס על **Leaflet** ו־**GitHub Pages**.  

## 🚀 איך לצפות במפה
האתר זמין בכתובת:  
https://mtsevgenei-source.github.io/war-update/

yaml
Copy code

---

## 📂 מבנה הקבצים
- `index.html` – קובץ המפה הראשי (לא צריך לשנות).  
- `updates.json` – קובץ הנתונים של העדכונים (זה הקובץ היחיד שיש לעדכן).  
- `ua.png` – אייקון צד אוקראיני.  
- `ru.png` – אייקון צד רוסי.  
- `nu.png` – אייקון ניטרלי/אזרחי.  

---

## ✏️ איך לעדכן את המפה
1. היכנס ל־GitHub → repository → קובץ `updates.json`.  
2. לחץ על האייקון של העיפרון (Edit).  
3. עדכן את הנקודות בפורמט JSON, למשל:

```json
[
  {
    "id": 1,
    "lat": 51.03,
    "lng": 34.68,
    "title": "קרבות ביונאקיבקה (סומי)",
    "date": "2025-08-22",
    "side": "ru",
    "front": "north",
    "media": {"type":"youtube", "id":"dQw4w9WgXcQ"},
    "summary": "כוחות סער רוסים מתקדמים לעומק יונאקיבקה, לחימה כבדה."
  }
]
