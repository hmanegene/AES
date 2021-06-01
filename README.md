# AES
AES CODING 
<!DOCTYPE html>
<html>
</body>
</html>
	<head>
		<meta charset="utf-6"/>
		<title>JavaScript File Encryption App</title>

		<meta name="viewport" content="width=device-width, initial-scale=1" />

		<link href="http://fonts.googleapis.com/css?family=Raleway:400,700" rel="stylesheet" />
		<link href="assets/css/style.css" rel="stylesheet" />

	</head>

	<body>

		<a class="back"></a>
		<div id="stage">
			<div id="step1">
				<div class="content">
					<h2>Encryption form</h2>
					<h2>Hilda Manegene</h2>
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value=" "><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value=" "><br><br>
</form> 
<a class="button encrypt red">Encrypt a file</a>
					<a class="button decrypt blue">Decrypt a file</a>
				</div>
			</div>
			<div id="step2">
				<div class="content if-encrypt">
					<h1>Choose a file to encrypt</h1>
					<h2>An encrypted file will be generated. No data retained in our server.</h2>
					<a class="button browse blue">Browse</a>
					<input type="file" id="encrypt-input" />
				</div>
				<div class="content if-decrypt">
					<h1>Choose a file to decrypt</h1>
					<h2>Only files encrypted with this tool are acceptable.</h2>
					<a class="button browse blue">Browse</a>

					<input type="file" id="decrypt-input" />
				</div>

			</div>

			<div id="step3">

				<div class="content if-encrypt">
					<h1>Enter a pass phrase</h1>
					<h2>This phrase will be used as an encryption key. Write it down or remember it; you won't be able to restore the file without it. </h2>

					<input type="password" />
					<a class="button process red">Encrypt!</a>
				</div>

				<div class="content if-decrypt">
					<h1>Enter the pass phrase</h1>
					<h2>Enter the pass phrase that was used to encrypt this file. It is not possible to decrypt it without it.</h2>

					<input type="password" />
					<a class="button process red">Decrypt!</a>
				</div>
			</div>

			<div id="step4">

				<div class="content">
					<h1>Your file is ready!</h1>
					<a class="button download green">Download</a>
				</div>

			</div>
		</div>

	</body>

	<!-- Include the AES algorithm of the crypto library -->
	<script src="assets/js/aes.js"></script>

	<script src="http://cdnjs.cloudflare.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
	<script src="assets/js/script.js"></script>

</html>
