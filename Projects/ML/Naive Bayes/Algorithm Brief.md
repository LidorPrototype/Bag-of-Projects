<div dir="rtl">
הסבר כללי על האלגוריתם בייסיאני נאיבי:

השם של האלגוריתם מגיע מהעובדה שהוא מניח שכול המשתנים לא תלויים אחד בשני, שזה בהרבה פעמים לא המקרה אבל עדיין לאלגוריתם הזה יש תוצאות מעולות לרוב.
האלגוריתם מחשב מה ההסתברות שנתון מסויים יופיע בהנחה שהוא שייך למשתנה מסויים, הוא מכפיל את זה על כול הנתונים שיש ואז כופל בהסתברות הקודמת של המשתנה ואז איזה חישוב שיצא הכי גבוה זאת תיהיה התוצאה שהוא ייתן (החיזוי)
הנוסחא של תיאוריית בייס היא:
\[ P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)} \]
