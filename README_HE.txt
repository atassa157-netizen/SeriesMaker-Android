SERIES MAKER ANDROID — v1

זהו פרויקט Android Studio מוכן שמארז את Series Maker כאפליקציה.

בניית APK:
1. פתח Android Studio.
2. Open > בחר את התיקייה SeriesMaker_Android_Project.
3. המתן ל-Gradle Sync.
4. Build > Build App Bundle(s) / APK(s) > Build APK(s).
5. Android Studio יציג קישור לקובץ app-debug.apk.

מה כלול:
- ממשק Series Maker מקומי בתוך האפליקציה.
- תסריט -> סצנות.
- דמויות מצוירות על ה-canvas ולכן הן חלק מתמונת הווידאו.
- עברית/אנגלית.
- 16:9 ו-9:16.
- תצוגה מקדימה וקריינות מערכת.
- יצוא WebM בסיסי.

מגבלה חשובה:
Android WebView/Chrome לא מבטיחים ש-SpeechSynthesis ייכנס ל-MediaRecorder.
כדי לקבל APK שמייצא תמיד סרטון עם קול מוטמע, יש להוסיף מנוע TTS/אודיו native או שרת/API
ולהרכיב את האודיו והווידאו. הפרויקט הזה אינו מציג את המגבלה כאילו היא פתורה.
