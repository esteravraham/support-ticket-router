# נתב פניות תמיכה: LLM ראשון בתוך גרף

נתב פניות תמיכה שבנוי כגרף LangGraph. מודל שפה מחליט לאיזה צוות כל פנייה שייכת: Billing, Tech או General. הפרויקט הוא מטלת בית בקורס סוכני AI.

- [`prompt.md`](prompt.md): המפרט הטכני שממנו נבנתה המחברת, כולל המודל שנבחר והנימוק.
- [`support_router.ipynb`](support_router.ipynb): המחברת, עם ציור הגרף ופניות הבדיקה.
- [פתיחה ב־Google Colab](https://colab.research.google.com/github/esteravraham/support-ticket-router/blob/main/support_router.ipynb)

## הרצה
המחברת קוראת את מפתח ה־API מ־Colab Secrets, ולכן המפתח לא נמצא בריפו. כדי להריץ, צריך להוסיף ב־Colab Secrets סוד בשם `OPENAI_API_KEY` עם מפתח OpenAI משלכם, ולהפעיל לו Notebook access.
