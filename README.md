<!DOCTYPE html>
<html dir="rtl" lang="he">
<head>
    <meta charset="UTF-8">
    <title>מערכת שמירת נתונים</title>
</head>
<body>
    <h1>ברוכים הבאים למערכת</h1>
    
    <!-- טופס התחברות -->
    <form id="loginForm">
        <h2>התחברות</h2>
        <input type="email" placeholder="אימייל" required>
        <input type="password" placeholder="סיסמה" required>
        <button type="submit">התחבר</button>
    </form>

    <!-- אזור תוכן -->
    <div id="contentArea">
        <h2>התוכן שלך</h2>
        <textarea id="userContent"></textarea>
        <button onclick="saveContent()">שמור</button>
    </div>
</body>
</html>
