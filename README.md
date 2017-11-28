<!DOCTYPE html>

<html>

<head>

</head>
<body>
<div class = "menu">
<?php include 'menu.php';?>
</div>
<form method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>
<form action="welcome.php" method="post">

<br><br>

<br><br>
<input type="submit">
</form>
<form action="upload.php" method="post" enctype="multipart/form-data">
    Select image to upload:
    <input type="file" name="fileToUpload" id="fileToUpload">
    <input type="submit" value="Upload Image" name="submit">
</form>
<p>Welcome</p>
<h1>This is a Heading</h1>
<p>This is a paragraph.<a href="https://www.w3schools.com">This is a link</a></p>
<?php include 'footer.php';?>

</body>
</html>
