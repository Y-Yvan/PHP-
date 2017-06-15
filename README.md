# PHP-
PHP实例源码
<!DOCTYPE html>
<html>
<head>
<title>E-Mail Form</title>
</head>
<body>
<form action="sendmail.php" method="POST">
<p><label for="name">Name:</label><br/>
<input type="text" size="25" id="name" name="name"/></p>
<p><label for="email">E-Mail Address:</label><br/>
<input type="text" size="25" id="email" name="email"/></p>
<p><label for="msg">Message:</label><br/>
<textarea id="msg" name="message" cols="30" rows="5"></textarea></p>
<button type="submit" name="submit" value="send">Send Message</button>
</form>
</body>
</html>




<!DOCTYPE html>
<html>
<head>
<title>A simple file upload form</title>
</head>
<body>
<form action="do_upload.php" enctype="multipart/form-data" method="POST">
<input type="hidden" name="MAX_FILE_SIZE" value="1048576"/>
<p><label for="fileupload">File to Upload:</label>
<input type="file" id="fileupload" name="fileupload"/></p>
<button type="submit" name="submit" value="send">Upload File</button>
</form>
</body>
</html>
