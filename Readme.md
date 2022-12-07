<!DOCTYPE html>
<html>
<head>
<title>Displaying Times and Dates</title>
</head>
<body>
<h1>Current Date and Time</h1>
<script type="text/javascript">
now = new Date();
localtime = now.toString();
utctime = now.toGMTString();
document.write("<strong>Local time:</strong> "
+ localtime + "<br/>");
document.write("<strong>UTC time:</strong> " + utctime);
// this is the current time according to my pc timezone//
hours = now.getHours();
mins = now.getMinutes();
secs = now.getSeconds();
milliseconds = now.getMilliseconds();
document.write("<h1>");
document.write(hours + ":" + mins + ":" + secs +  milliseconds);
/* i go like learn more about js*/
document.write("</h1>");
</script>
</body>
</html>
