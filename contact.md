---
layout: page
title: Contact
---

<div id="rightFormBox" class="clearfix">

	<form action="/contact.php" method="post" name="contactForm" id="contactForm">
												
		<!--NAME-->
		<div id="nameBox" class="first formbox clearfix">
			<label for="name">Name</label>
			<input class="inputfield" type="text" name="name" id="name"/>	
		</div>

		<!--EMAIL-->
		<div id="emailBox" class="formbox clearfix">
			<label for="email">E-Mail</label>
			<input class="inputfield" type="text" name="email" id="email"/>	
		</div>

		<!--MESSAGE-->
		<div id="messageBox" class="formbox clearfix">
			<label for="message">Message</label>
			<textarea rows="10" name="comingMessage" id="comingMessage">Message Here</textarea>
		</div>

		<!--SUBMIT-->
		<input id="clear_btn" type="reset" name="submit" value="clear"> 
		<input id="submit_btn" type="submit" name="submit" value="submit"> 
	</form>
</div>
