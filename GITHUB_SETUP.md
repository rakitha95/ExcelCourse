# הוראות לפרסום הקורס ב-GitHub

## שלב 1: יצירת Repository ב-GitHub

1. **היכנס ל-GitHub:**
   - פתח דפדפן והיכנס ל-https://github.com
   - התחבר עם המשתמש שלך: `ziv-gabel`

2. **צור Repository חדש:**
   - לחץ על הכפתור הירוק "New" או "+" בפינה הימנית העליונה
   - בחר "New repository"

3. **הגדר את ה-Repository:**
   - **Repository name:** `ExcelCourse`
   - **Description:** `קורס Excel מקיף בעברית - מהבסיס ועד טבלאות פיווט`
   - **Visibility:** Public (מומלץ) או Private (אם אתה רוצה)
   - **אל תסמן** "Add a README file" (כבר יש לנו)
   - **אל תסמן** "Add .gitignore" (כבר יש לנו)
   - **אל תסמן** "Choose a license" (אופציונלי)

4. **לחץ על "Create repository"**

## שלב 2: חיבור ה-Repository המקומי ל-GitHub

לאחר יצירת ה-Repository, GitHub יציג לך הוראות. השתמש בפקודות הבאות:

```bash
# הוסף את ה-remote origin
git remote add origin https://github.com/ziv-gabel/ExcelCourse.git

# דחוף את הקוד ל-GitHub
git push -u origin main
```

## שלב 3: הגדרת Repository

### הוסף תיאור מפורט:
1. היכנס ל-Repository שיצרת
2. לחץ על "About" בצד ימין
3. הוסף תיאור מפורט:
   ```
   קורס Excel מקיף בעברית הכולל:
   📚 מבוא ל-Excel והממשק
   📊 נוסחאות ופונקציות מתקדמות
   📈 גרפים ודיאגרמות
   🔄 טבלאות פיווט מתקדמות
   💡 8 תרגילים מעשיים
   ⌨️ קיצורי מקלדת מקיפים
   ```

### הוסף תגיות (Topics):
הוסף את התגיות הבאות:
- `excel`
- `hebrew`
- `course`
- `tutorial`
- `pivot-tables`
- `formulas`
- `data-analysis`
- `israel`

## שלב 4: עיצוב ה-README

ה-README.md כבר מוכן, אבל אתה יכול להוסיף:

### תמונת כותרת:
```markdown
# קורס Excel מקיף בעברית 📊

![Excel Course](https://img.shields.io/badge/Excel-Course-blue?style=for-the-badge&logo=microsoft-excel)
![Hebrew](https://img.shields.io/badge/Language-Hebrew-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey?style=for-the-badge)
```

### סטטיסטיקות:
```markdown
![GitHub stars](https://img.shields.io/github/stars/ziv-gabel/ExcelCourse)
![GitHub forks](https://img.shields.io/github/forks/ziv-gabel/ExcelCourse)
![GitHub issues](https://img.shields.io/github/issues/ziv-gabel/ExcelCourse)
```

## שלב 5: פרסום ושיתוף

### 1. שתף ב-LinkedIn:
פוסט מומלץ:
```
🚀 שמח לשתף איתכם קורס Excel מקיף בעברית שיצרתי!

📚 הקורס כולל:
• מבוא ל-Excel והממשק
• נוסחאות ופונקציות מתקדמות  
• גרפים ודיאגרמות
• טבלאות פיווט מתקדמות
• 8 תרגילים מעשיים
• קיצורי מקלדת מקיפים

🎯 מתאים למתחילים ומתקדמים כאחד!

🔗 הקורס זמין ב-GitHub: [קישור]

#Excel #DataAnalysis #Hebrew #Tutorial #Israel
```

### 2. שתף בפורומים:
- Excel Forum ישראל
- פורומי פיתוח ישראלים
- קבוצות LinkedIn רלוונטיות

### 3. עדכן את הפרופיל שלך:
הוסף את הקורס לפרופיל GitHub שלך כ-"Pinned repository"

## שלב 6: תחזוקה עתידית

### עדכונים:
```bash
# לאחר שינויים בקוד
git add .
git commit -m "Update: [תיאור השינוי]"
git push
```

### Issues ו-Pull Requests:
- עקוב אחרי Issues שמשתמשים פותחים
- תן תשובות מהירות
- קבל Pull Requests לשיפורים

### Analytics:
- עקוב אחרי מספר ה-views
- בדוק איזה קבצים פופולריים
- למד מהפידבק

---

## קישורים שימושיים

- **Repository:** https://github.com/ziv-gabel/ExcelCourse
- **Issues:** https://github.com/ziv-gabel/ExcelCourse/issues
- **Discussions:** https://github.com/ziv-gabel/ExcelCourse/discussions

---

**בהצלחה! 🚀**

*זכור: הקורס שלך יכול לעזור לאנשים רבים ללמוד Excel. שתף אותו בגאווה!* 