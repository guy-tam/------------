# Sample Streamlit Dashboard

דשבורד אינטראקטיבי קטן שנבנה עם **Streamlit** ומציג:
- כרטיסי KPI (מדדים)
- גרף קווי לפי מטריקה שנבחרת בסיידבר
- טבלת נתונים

> הקוד משתמש בנתוני דוגמה (DataFrame) כדי להדגים UI וויזואליזציה.

---

## Demo / מה רואים?

- **Filters בסיידבר**: בחירת מטריקה להצגה (`Sales` / `Revenue` / `Users` / `Engagement`)
- **KPIs**: סכומים/ממוצעים מהירים למעלה
- **Chart**: גרף Plotly לאורך חודשים
- **Table**: תצוגת הנתונים המלאה

---

## Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **Plotly Express**

---

## התקנה (מומלץ עם venv)

```bash
python -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install streamlit pandas plotly
```

---

## הרצה

```bash
streamlit run deshbord.py
```

לאחר ההרצה, Streamlit יפתח כתובת מקומית (בד״כ `http://localhost:8501`).

---

## מבנה הפרויקט

- `deshbord.py` – האפליקציה הראשית (דשבורד Streamlit)
- `tetst.py` – קובץ בדיקה/דוגמה

---

## פריסה ל־GitHub + Streamlit Cloud (אופציונלי)

כדי לפרוס בקלות:

1. להעלות את הפרויקט ל־GitHub
2. להיכנס ל־Streamlit Community Cloud
3. לבחור את הריפו והקובץ הראשי: `deshbord.py`

טיפ: מומלץ להוסיף `requirements.txt` כדי שהפריסה תדע להתקין תלויות.

---

## Roadmap (רעיונות לשדרוג)

- חיבור לקובץ CSV/DB במקום נתוני דוגמה
- עוד סוגי גרפים (Bar, Area, KPI trends)
- פילטר לפי טווח תאריכים/חודש
- עיצוב מתקדם עם `st.container`, `st.tabs`, ו־Theme

---

## License

MIT (או כל רישיון שתבחר/י)

