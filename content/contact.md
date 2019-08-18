---
title: 'Contact'
layout: contact
#menu: 'main'
---

For any inquiries and to join our mailing list, shoot us an email with this
form. One of our supervisors will get back to you.

<form method="post" action="https://formspree.io/supervisors@ryersonbikes.com">
	<div class="row">
		<div class="6u 12u$(mobile)"><input type="text" name="name" placeholder="Name" />
		</div>
		<div class="6u$ 12u$(mobile)"><input type="text" name="email" placeholder="Email" />
		</div>
		<div class="12u$">
			<textarea name="message" placeholder="Message"></textarea>
		</div>
		<div class="12u$">
			<input type="submit" value="Send Message" />
		</div>
	</div>
</form>

/* Form */

	form label {
		display: block;
		text-align: left;
		margin-bottom: 0.5em;
	}

	form input[type="text"],
	form input[type="email"],
	form input[type="password"],
	form select,
	form textarea {
		position: relative;
		-webkit-appearance: none;
		display: block;
		border: 0;
		outline: 0;
		background: #fff;
		background: rgba(255, 255, 255, 0.75);
		width: 100%;
		border-radius: 0.35em;
		padding: 0.75em 1em 0.75em 1em;
		box-shadow: inset 0 0.1em 0.1em 0 rgba(0, 0, 0, 0.05);
		border: solid 1px rgba(0, 0, 0, 0.15);
		-moz-transition: all 0.35s ease-in-out;
		-webkit-transition: all 0.35s ease-in-out;
		-ms-transition: all 0.35s ease-in-out;
		transition: all 0.35s ease-in-out;
	}

		form input[type="text"]:focus,
		form input[type="email"]:focus,
		form input[type="password"]:focus,
		form select:focus,
		form textarea:focus {
			box-shadow: 0 0 2px 1px #8ebebc;
			background: #fff;
		}

	form input[type="text"],
	form input[type="email"],
	form input[type="password"],
	form select {
		line-height: 1.25em;
	}

	form textarea {
		min-height: 14em;
	}

	form .formerize-placeholder {
		color: #555 !important;
	}

	form ::-webkit-input-placeholder {
		color: #555 !important;
	}

	form :-moz-placeholder {
		color: #555 !important;
	}

	form ::-moz-placeholder {
		color: #555 !important;
	}

	form :-ms-input-placeholder {
		color: #555 !important;
	}

	form ::-moz-focus-inner {
		border: 0;
	}
