<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>bai02 - html va php</title>
</head>
<body>
    <!-- Header -->
    <?php require_once './inc/header.php'?>
    <?php require_once './inc/header.php'?>
    <h1>html va php</h1>
    <?php echo 'Hello world'?>
    <?php 
        $language='Ngon ngu lap trinh php';
        var_dump($language);
    ?>
    <?php require_once './inc/content.php';?>
    <?php require_once './inc/content.php';?>
    <!-- footer-->
    <?php require_once './inc/footer.php'?>
    <?php require_once './inc/footer.php'?>
</body>
</html>
