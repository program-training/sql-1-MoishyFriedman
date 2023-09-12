[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11824334&assignment_repo_type=AssignmentRepo)
<div dir="rtl">

## תרגול SQL

את כל התשובות אתם כותבים בקובץ solutions.txt, לפי ההוראות ששם.

את השאילתות מריצים ב-pgadmin על הדאטהבייס של northwind

**הערה**: בכל השאילתות בהם אתם נדרשים להביא את כל המידע לאחר שבחרתם הכל בעזרת * נסו להביא גם רק חלקים מהמידע. 
לדוגמה אם הייתה לכם שאילתה שבה ביצעתם `SELECT * FROM Products`
בצעו ישר אחרי `SELECT ProductID,ProductName FROM Products`

---
### שאלות
---
1. אחזר את ProductID,ProductName,CategoryID כל המוצרים מטבלת Products שמחיר היחידה שלהם גדול מ-50 דולר.
   

2. אחזר את כל הלקוחות מטבלת Customers מאזור 'גרמניה'. Country = Germany
3. אחזר את כל ההזמנות מטבלת Orders שהוזמנו על ידי לקוח מסוים (לדוגמה, CustomerID = ALFKI)
4. אחזר את הסכום הכולל של ההזמנות עבור כל לקוח. תחת השם TotalOrders
5. אחזר את חמשת המוצרים היקרים ביותר.
6. אחזר את כל העובדים שנולדו לפני שנת 1960. מטבלת Employees
7. אחזר את כל המוצרים שאין במלאי (יחידות במלאי = 0).
8. אחזר את המחיר הממוצע של כל המוצרים.
9.  אחזר את הסכום הכולל שנרוויח ממוצר מסוים (לדוגמה, ProductID 7) בהתבסס על כמות ההזמנות ומחיר היחידה. מטבלת OrderDetails
10. אחזר את מספר הקטגוריות המובלטות של המוצרים.
11. אחזר את כל המוצרים שכבר לא מסופקים Discontinued = 1
12. אחזר את כמות ההזמנות משנת 1997 חפשו על YEAR
13. אחזרו את כל הלקוחות שהתואר - ContactTitle - שלהם הוא Owner או CEO חפשו על IN
14. אחזרו את המוצר היקר ביותר 
15. אחזרו את ממוצע העובדים.
16. אחזרו את כל הלקוחות שמספר הטלפון שלהם מכיל 123. קראו על LIKE
17. אחזרו את כל המוצרים שיש להם פחות מ 10 יחידות במלאי ועדיין מסופקים
18. אחזרו את המחיר המקסימלי כ HighestPrice והמחיר המינימלי כ LowestPrice 
19. אחזר את כל ההזמנות מהתאריך 05-05-1997
20. אחזר טבלת מוצר וכמות ליחידה
21. כתוב שאילתה כדי לקבל רשימת מוצרים (מזהה, שם, מחיר יחידה) במחיר גבוה מהממוצע.
22. אחזר את מספר העובדים מכל עיר
</div>