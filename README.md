# Spaceship-Game

<div dir="rtl" lang="he">

# HW4-QA.3
 

 הוא משחק על חללית שמטרתו שהחללית תירה חיצי לייזר ותפגע באויבים הבאים לכיוונה.
 לשחקן יש 3 פסילות אפשריות, כלומר יש לו עד 3 פעמים שבהם יוכל לפגוע בו אויב. אם פגעו בחללית יותר מ3 פעמים השחקן יפסיד. במהלך המשחק השחקן צובר נקודות על ידי פגיעה באויבים. כדי לנצח, על השחקן להצליח להגיע לחץ שנמצא במסך.

## השינויים שביצעתי בקוד של המרצה הם:
1)
במשחק הקודם השחקן היה נפסל לאחר פעם אחת שפגעה בו החללית, אצלי במשחק לשחקן יש 3 פסילות אפשריות שרק בפעם השלישית השחקן יפסיד. 
את השינוי הזה ביצעתי בסקריפט הקיים: GameOverOnTrigger2D.
הוספתי פונקציית עזר ברגע שהכללית פוגעת ביריב היא מורידה ממספר החיים שלו והגדרתי שהמקסימום יהיה 3. 
 
2)
הוספתי מד חיים , ברגע שהשחקן התנגש במכונית ירד לו 1/3 מהמד חיים.
כרגע לשחקן יש 3 פסילות.
כאשר יפסל 3 פעמים המד יתרוקן כולו.
 ![](https://github.com/KoralElbaz/Spaceship-Game/blob/main/Assets/Images/healthBar.PNG)
 
3)
בנוסף הוסף מסך סצינה נוסף , כאשר נגמר לשחק החיים והמד מתרוקן כולו נגיע למסך שבו המסך נגמר.
 
## במשחק קיימים שני מסכים
 
### מסך המשחק
שבו נראה את החללית והיריבים שיורידים לכיוונה
 ![](https://github.com/KoralElbaz/Spaceship-Game/blob/main/Assets/Images/gameScreen.PNG)
 
### מסך סיום המשחק
![](https://github.com/KoralElbaz/Spaceship-Game/blob/main/Assets/Images/gameOver.PNG)
 
 
[לחץ כאן על מנת לעבור לסקריפט שבו בוצעו השינויים](https://github.com/KoralElbaz/Spaceship-Game/blob/main/Assets/Scripts/GameOverOnTrigger2D.cs)
 
[לחץ כאן על מנת לעבור לסקריפט שבו בוצעו השינויים](https://github.com/KoralElbaz/Spaceship-Game/blob/main/Assets/HealthBar.cs) 

 
 
 [The Game- למעבר למשחק לחץ כאן](https://sivan-koral.itch.io/spaceship-game)
 
 



</div>
