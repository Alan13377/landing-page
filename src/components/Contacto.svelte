<div class="container">
	<form class="contact" action="" method="post">
		<h3>Contactanos</h3>

		<fieldset>
			<input placeholder="Nombre" type="text" required />
		</fieldset>
		<fieldset>
			<input placeholder="Email" type="email" required />
		</fieldset>
		<fieldset>
			<input placeholder="Numero Telefono" type="tel" required />
		</fieldset>
		<fieldset>
			<textarea placeholder="Escribe tu mensaje...." required />
		</fieldset>
		<fieldset>
			<button name="submit" type="submit" id="contact-submit" data-submit="...Sending"
				>Enviar</button
			>
		</fieldset>
	</form>
</div>

<style>
	.container {
		max-width: 1200px;
		width: 100%;
		margin: 0 auto;
		position: relative;
	}

	.contact input[type='text'],
	.contact input[type='email'],
	.contact input[type='tel'],
	.contact textarea,
	.contact button[type='submit'] {
		font: 400 12px/16px 'Open Sans', Helvetica, Arial, sans-serif;
	}

	.contact {
		background: #f9f9f9;
		padding: 25px;
		margin: 50px 0;
	}

	.contact h3 {
		color: #f96;
		display: block;
		font-size: 30px;
		font-weight: 400;
	}

	fieldset {
		border: medium none !important;
		margin: 0 0 10px;
		min-width: 100%;
		padding: 0;
		width: 100%;
	}

	.contact input[type='text'],
	.contact input[type='email'],
	.contact input[type='tel'],
	.contact textarea {
		width: 100%;
		border: 1px solid #ccc;
		background: #fff;
		margin: 0 0 5px;
		padding: 10px;
	}

	.contact input[type='text']:hover,
	.contact input[type='email']:hover,
	.contact input[type='tel']:hover,
	.contact textarea:hover {
		-webkit-transition: border-color 0.3s ease-in-out;
		-moz-transition: border-color 0.3s ease-in-out;
		transition: border-color 0.3s ease-in-out;
		border: 1px solid #aaa;
	}

	.contact textarea {
		height: 100px;
		max-width: 100%;
		resize: none;
	}

	.contact button[type='submit'] {
		cursor: pointer;
		width: 100%;
		border: none;
		background: #0cf;
		color: #fff;
		margin: 0 0 5px;
		padding: 10px;
		font-size: 15px;
	}

	.contact button[type='submit']:hover {
		background: #09c;
		-webkit-transition: background 0.3s ease-in-out;
		-moz-transition: background 0.3s ease-in-out;
		transition: background-color 0.3s ease-in-out;
	}

	.contact button[type='submit']:active {
		box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.5);
	}

	.contact input:focus,
	.contact textarea:focus {
		outline: 0;
		border: 1px solid #999;
	}
	::-webkit-input-placeholder {
		color: #888;
	}
	:-moz-placeholder {
		color: #888;
	}
	::-moz-placeholder {
		color: #888;
	}
	:-ms-input-placeholder {
		color: #888;
	}
</style>
