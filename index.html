<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- oqem vfqo amgh seko -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/toastify-js/src/toastify.min.css">
    <script src="https://cdn.jsdelivr.net/npm/toastify-js"></script>
</head>

<body>
    <form action="" method="post">
        <div class="form-group">
            <input type="text" name="name" id="" placeholder="name">
            <br>
            <input type="email" name="email" id="" placeholder="email">
            <br>
            <input type="text" name="subject" placeholder="subject">
            <br>
            <textarea id="" cols="" name="message" rows="3" placeholder="message"></textarea>
            <br>
            <input type="submit" name="send" value="send">
        </div>
    </form>
    <?php

    use PHPMailer\PHPMailer\PHPMailer;
    use PHPMailer\PHPMailer\SMTP;
    use PHPMailer\PHPMailer\Exception;

    if(isset($_POST['send'])){
        $name = isset($_POST["name"]) ? htmlspecialchars($_POST["name"]) : '';
        $email = isset($_POST["email"]) ? filter_var($_POST["email"], FILTER_SANITIZE_EMAIL) : '';
        $subject = isset($_POST["subject"]) ? htmlspecialchars($_POST["subject"]) : '';
        $message = isset($_POST["message"]) ? htmlspecialchars($_POST["message"]) : '';

        // Load PHPMailer classes
        require 'PHPMailer/Exception.php';
        require 'PHPMailer/PHPMailer.php';
        require 'PHPMailer/SMTP.php';
        
        // Create a new PHPMailer instance
        $mail = new PHPMailer(true);
        
        try {
            // Server settings
            // $mail->SMTPDebug = SMTP::DEBUG_SERVER; // Enable verbose debug output
            $mail->isSMTP(); // Send using SMTP
            $mail->Host       = 'smtp.gmail.com'; // Set the SMTP server to send through
            $mail->SMTPAuth   = true; // Enable SMTP authentication
            $mail->Username   = 'devloper.ds@gmail.com'; // SMTP username
            $mail->Password   = 'oqem vfqo amgh seko'; // SMTP password (replace this with a secure app password)
            $mail->SMTPSecure = PHPMailer::ENCRYPTION_SMTPS; // Enable implicit TLS encryption
            $mail->Port       = 465;

            // Recipients
            $mail->setFrom('devloper.ds@gmail.com', 'Contact Us');
            $mail->addAddress('devloper.ds@gmail.com', 'Joe User'); // Add a recipient
            
            // Content
            $mail->isHTML(true); // Set email format to HTML
            $mail->Subject = $subject; // Use the subject from the form
            $mail->Body    = "Name: $name<br>Email: $email<br>Message: $message"; // Build the email body
            
            $mail->send();
            echo "<script>var mailSuccess = true;</script>";
        } catch (Exception $e) {
            echo "<script>var mailSuccess = false;</script>";
        }
    }
    ?>
    <script>
        if (typeof mailSuccess !== 'undefined') {
            if (mailSuccess) {
                Toastify({
                    text: "Email sent successfully!",
                    duration: 3000,
                    close: true,
                    gravity: "top",
                    position: "center",
                    backgroundColor: "linear-gradient(to right, #00b09b, #96c93d)",
                    stopOnFocus: true,
                }).showToast();
            } else {
                Toastify({
                    text: "Failed to send email. Try again!",
                    duration: 3000,
                    close: true,
                    gravity: "top",
                    position: "center",
                    backgroundColor: "linear-gradient(to right, #ff5f6d, #ffc371)",
                    stopOnFocus: true,
                }).showToast();
            }
        }
    </script>
</body>

</html>