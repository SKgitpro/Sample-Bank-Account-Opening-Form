<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible"
		content="IE=edge">
	<meta name="viewport"
		content="width=device-width, initial-scale=1.0">
	<title>
		Account opening form 
	</title>

	<style>
		/* Styling the Body element 
		i.e. Color, Font, Alignment */
		body {
			background-color: #05c46b;
			font-family: Verdana;
			text-align: center;
		}

		/* Styling the Form (Color, Padding, Shadow) */
		form {
			background-color:lightgray;
			max-width: 500px;
			margin: 50px auto;
			padding: 30px 20px;
			box-shadow: 2px 5px 10px rgba(0, 0, 0, 0.5);
		}

		/* Styling form-control Class */
		.form-control {
			text-align: left;
			margin-bottom: 25px;
		}

		/* Styling form-control Label */
		.form-control label {
			display: block;
			margin-bottom: 10px;
			color:dark black;
		}

		/* Styling form-control input, 
		select, textarea */
		.form-control input,
		.form-control select,
		.form-control textarea {
			border: 1px solid #777;
			border-radius: 2px;
			font-family: inherit;
			padding: 10px;
			display: block;
			width: 95%;
		}

		/* Styling form-control Radio 
		button and Checkbox */
		.form-control input[type="radio"],
		.form-control input[type="checkbox"] {
			display: inline-block;
			width: auto;
		}

		/* Styling Button */
		button {
			background-color: #05c46b;
			border: 1px solid #777;
			border-radius: 2px;
			font-family: inherit;
			font-size: 21px;
			display: block;
			width: 100%;
			margin-top: 50px;
			margin-bottom: 20px;
		}
	</style>
</head>

<body>
	<h1>Account Opening Form</h1>
	<h2>For indivisuals & sole proprietorships</h2>

	<img src="Banklogo.png">

	<!-- Create Form -->
	<form id="form">

		<!-- Account types -->

		<div class="form-control">
			<label for="name" id="label-name">
				Account Number
				(for Bank use only):
			</label>

			<!-- Input Type Text -->
			<input type="text" id="name"
				placeholder="  " />
		</div>

		<div class="form-control">
			<label for="name" id="label-name">
				IBAN:
				(for Bank use only):
			</label>

			<!-- Input Type Text -->
			<input type="text" id="name"
				placeholder="  " />
		</div>

		<div class="form-control">
			<label for="name" id="label-name">
				Title of Account:
				(as per identity document):
			</label>

			<!-- Input Type Text -->
			<input type="text" id="name"
				placeholder="  " />
		</div>

		<div class="form-control">
			<label for="name" id="label-name">
				Nature of Account:
			</label>

			<select name="role" id="role">
				<option value="student">Indivisual</option>
				<option value="intern">Proprietership</option>
				<option value="professional">Minor</option>
				<option value="other">Other</option>
			</select>
		</div>

		<div class="form-control">
			<label for="name" id="label-name">
				Type of Account:
			</label>

			<select name="role" id="role">
				<option value="student">Current</option>
				<option value="intern">Current Plus</option>
				<option value="professional">Savings</option>
				<option value="professional">Monthly Saver</option>
				<option value="other">Other</option>
			</select>
		</div>
             <!--Personal Details -->
             <h1>Personal Information</h1>
		<div class="form-control">
			<label for="name" id="label-name">
				Name:
			</label>

			<!-- Input Type Text -->
			<input type="text" id="name"
				placeholder="Enter your name" />
		</div>

<div class="form-control">
			<label for="name" id="label-name">
				Gender:
			</label>

			<select name="role" id="role">
				<option value="student">Male</option>
				<option value="intern">Female</option>
			</select>
		</div>

		<div class="form-control">
			
		<label for="birthday">Date of Birt:</label>
        <input type="date" id="birthday" name="birthday">
		</div>

		<div class="form-control">
			<label for="email" id="label-email">
				Email
			</label>

			<!-- Input Type Email-->
			<input type="email" id="email"
				placeholder="Enter your email" />
		</div>

		<div class="form-control">
			<label for="age" id="label-age">
				Age
			</label>

			<!-- Input Type Text -->
			<input type="text" id="age"
				placeholder="Enter your age" />
		</div>

		<div class="form-control">
			<label for="role" id="label-role">
				Nationality:
			</label>

			<!-- Dropdown options -->
			<select name="role" id="role">
				<option value="student">Pakistani</option>
				<option value="other">Other</option>
			</select>
		</div>

		<div class="form-control">
			<label for="name" id="label-name">
				Phone Number:
			</label>

			<!-- Input Type Text -->
			<input type="text" id="name"
				placeholder="Enter your phone number" />
		</div>

		<div class="form-control">
			<label>
				Would you like to request for ATM/Debit Card?
			</label>

			<!-- Input Type Radio Button -->
			<label for="recommed-1">
				<input type="radio" id="recommed-1"
					name="recommed">Yes
				</input>
			</label>
			<label for="recommed-2">
				<input type="radio" id="recommed-2"
					name="recommed">No
				</input>
			</label>
			<label for="recommed-3">
				<input type="radio" id="recommed-3"
					name="recommed">Maybe
				</input>
			</label>
		</div>

		<div class="form-control">
			<label>ATM/Debit Card for Domestic use only:
				<small>(Check all that apply)</small>
			</label>
			<!-- Input Type Checkbox -->
			<label for="inp-1">
				<input type="checkbox" name="inp">PAYPAK
				</input>
           </label>

			<label>ATM/Debit Card for International & Domestic use:
			</label>
			<label for="inp-2">
				<input type="checkbox" name="inp">Union Pay
				</input>
			</label>
			<label for="inp-3">
				<input type="checkbox" name="inp">VISA Gold
				</input>
			</label>
			<label for="inp-4">
				<input type="checkbox" name="inp">VISA Silver
				</input>
			</label>
			<label for="inp-5">
				<input type="checkbox" name="inp">VISA Platinum
				</input>
			</label>
			<label for="inp-6">
				<input type="checkbox" name="inp">JavaScript
				</input>
			</label>
			<label for="inp-7">
				<input type="checkbox" name="inp">Other
				</input>
			</label>
		</div>

		<div class="form-control">
			<label for="comment">
				Any comments or suggestions:
			</label>

			<!-- multi-line text input control -->
			<textarea name="comment" id="comment"
					placeholder="Enter your comment here">
			</textarea>
		</div>

		<!-- Multi-line Text Input Control -->
		<button type="submit" value="submit">
			Submit
		</button>
	</form>
</body>

</html>
