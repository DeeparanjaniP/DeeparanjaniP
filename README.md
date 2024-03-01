<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>DARPG Portal Dashboard</title>
 <style>
 /* Basic styles for layout */
 body {
 font-family: Arial, sans-serif;
margin: 0;
 padding: 0;
 }
 .container {
 max-width: 1200px;
 margin: 0 auto;
 padding: 20px;
 }
 .header {
 background-color: #333;
 color: #fff;
 padding: 10px 0;
 text-align: center;
  }
 .menu {
 float: left;
 width: 20%;
 background-color: #f4f4f4;
 padding: 20px;
 }
 .content {
 float: left;
 width: 80%;
 padding: 20px;
 }
 /* Styles for menu items */
 .menu ul {
 list-style-type: none;
 padding: 0;
 }
 .menu ul li {
 margin-bottom: 10px;
 }
 .menu ul li a {
 color: #333;
 text-decoration: none;
  display: block;
 }
 .menu ul li a:hover {
 color: #666;
 }
 /* Styles for dashboard widgets*/
 widget {
 background-color: #fff;
 border: 1px solid #ccc;
 padding: 20px;
 margin-bottom: 20px;
 }
 .widget h2 {
 margin-top: 0;
 }
 </style>
</head>
<body>
 <div class="header">
 <h1>DARPG Portal Dashboard</h1>
  </div>
 <div class="container">
 <div class="menu">
 <ul>
 <li><a href="#overview">Overview</a></li>
 <li><a href="#reports">Reports</a></li>
 <li><a href="#analytics">Analytics</a></li>
  <li><a href="#settings">Settings</a></li>
 </ul>
 </div>
 <div class="content">
 <div id="overview" class="widget">
 <h2>Overview</h2>
 <p>This section provides an overview of the DARPG portal.</p>
 </div>
 <div id="reports" class="widget">
 <h2>Reports</h2>
 <p>This section displays various reports related to government activities.</p>
 </div>
 <div id="analytics" class="widget">
 <h2>Analytics</h2>
 <p>This section contains analytics and insights derived from data.</p>
 </div>
 <div id="settings" class="widget">
 <h2>Settings</h2>
 <p>This section allows users to customize their dashboard settings.</p>
 </div>
 </div>
 </div>
</body>
</html>
