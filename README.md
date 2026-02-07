# Smart-Forum-
Smart Forum 
<!DOCTYPE html>
<html>
<head>
<style>

body{
margin:0;
font-family:Arial, sans-serif;
background:#EEE9DF;
display:flex;
height:100vh;
}

/* LEFT MENU */

.sidebar{
width:240px;
background:#2C3B4D;
color:white;
padding:20px;
display:flex;
flex-direction:column;
gap:20px;
}

.logo{
font-size:22px;
font-weight:bold;
color:#FFB162;
margin-bottom:20px;
}

.menu-item{
padding:10px;
background:#1B2632;
border-radius:8px;
cursor:pointer;
}

.menu-item:hover{
background:#A35139;
}

/* MAIN AREA */

.main{
flex:1;
display:flex;
flex-direction:column;
}

/* TOP BAR */

.topbar{
background:#C9C1B1;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
}

.mood{
font-weight:bold;
}

.emojis span{
font-size:24px;
margin-left:10px;
cursor:pointer;
}

/* WIDGET AREA */

.content{
flex:1;
display:flex;
gap:20px;
padding:20px;
}

.widget{
flex:1;
background:white;
border-radius:12px;
padding:20px;
box-shadow:0px 2px 6px rgba(0,0,0,0.1);
}

/* CALENDAR MOCK */

.calendar{
height:300px;
background:#EEE9DF;
border-radius:8px;
display:flex;
align-items:center;
justify-content:center;
}

/* MESSAGE BOARD */

.messages{
display:flex;
flex-direction:column;
gap:10px;
}

.message{
background:#FFB162;
padding:10px;
border-radius:8px;
color:#1B2632;
}

</style>
</head>

<body>

<!-- SIDEBAR -->

<div class="sidebar">
<div class="logo">Smart Forum</div>

<div class="menu-item">Create a Group</div>
<div class="menu-item">Messages</div>
<div class="menu-item">Groups</div>
<div class="menu-item">Roles</div>
<div class="menu-item">Templates</div>
<div class="menu-item">Emotional Check-in</div>

</div>

<!-- MAIN -->

<div class="main">

<div class="topbar">

<div class="mood">
Set the mood today
</div>

<div class="emojis">
<span>😀</span>
<span>😐</span>
<span>😞</span>
</div>

</div>

<div class="content">

<!-- CALENDAR -->

<div class="widget">
<h3>Task Calendar</h3>
<div class="calendar">
Calendar Widget (Prototype)
</div>
</div>

<!-- MESSAGE BOARD -->

<div class="widget">
<h3>Recent Messages</h3>

<div class="messages">
<div class="message">Teacher: Reminder about project deadline.</div>
<div class="message">Classmate: Can we meet tomorrow?</div>
<div class="message">Teacher: Feedback uploaded.</div>
</div>

</div>

</div>

</div>

</body>
</html>
