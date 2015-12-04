---
layout: page
title: Contact
---
<p class="message">Contact us to begin the journey</p>

<p>
<form id="contactform" action="//formspree.io/justinseiser@gmail.com" method="POST">

	<input type="hidden" name="_subject" value="Website contact" />
	<input type="text" name="_gotcha" style="display:none" />
	<p>
		<label for="name">Name</label>
		<input type="text" name="name" placeholder="Name" required maxlength="30" />
	</p>

	<p>
		<label for="email">Email</label>
		<input type="email" name="email" placeholder="your@email.address" required maxlength="50" />
	</p>

	<p>
  		<label for="message">Message</label>
  		<p>
  			<textarea type="email" name="message" placeholder="Your message" required ></textarea>
  		</p>
	</p>

	<p>
		<input type="submit" value="Send">
	</p>
</form>
</p>