---
title: "Get Started"
description:
layout: simple
sharingLinks: false
---
<!-- Make sure you don't change the form action-->
<form action="https://api.staticforms.xyz/submit" method="post">
<!-- hidden fields & Attributes -->
<input type="hidden" name="accessKey" value="fd1b3bd8-e54c-4528-8286-aa1f33110a4d">
<input type="hidden" name="subject" value="Contact Form - egcs.health" />
<input type="text" name="replyTo" value="info@egcs.health" style="display:none">
<input type="hidden" name="redirectTo" value="https://dev.egcs.health/contact/success">
<!-- Data Fields -->
<div class="box-contact-us">
<div>
<label for="fname">First Name</label><br />
<input type="text" id="fname" name="$First_Name" placeholder="First Name" required>
</div>
<div>
<label for="fname">Last Name</lable> <br />
<input type="text" id="lname" name="$Last_Name" placeholder="Last Name" required>
</div>
<div>
<label for="phone">Phone Number</lable> <br />
<input type="tel" id="phone" name="phone" placeholder="Phone Number" required>
</div>
<div>
<label for="email">Email</lable> <br />
<input type="email" id="email" name="email" placeholder="Email" required>
</div>
<div>
<label>I Am Interested in:</label> <br />
<input type="checkbox" name="$interested_in" id="Individual Counseling" value="Individual Counseling"> <label for="Individual Counseling">Individual Counseling</label> <br />
<input type="checkbox" name="$interested_in" id="Couples Counseling" value="Couple’s Counseling"> <label for="Couples Counseling">Couples Counseling</label> <br />
<input type="checkbox" name="$interested_in" id="Anger Management" value="Anger Management Classes"> <label for="Anger Management">Anger Management Classes</label> <br />
<input type="checkbox" name="$interested_in" id="Supervision" value="Clinical Supervision"> <label for="Supervision">Clinical Supervision</label>
</div>
<div>
<label>How did you find us?</lable> <br />
<input type="radio" name="$How_Did_You_Find_Us" value="Google Search" id="Google Search"> <label for="Google_Seach">Google Search</lable> <br />
<input type="radio" name="$How_Did_You_Find_Us" value="Word of Mouth" id="Word of Mouth"> <label for="Word_of_Mouth">Word of Mouth</lable> <br />
<input type="radio" name="$How_Did_You_Find_Us" value="Community Event" id="Community_Event"> <label for="Community_Event">Community Event</lable><br />
</div>
<div>
<label for="message">What are two things you're currently struggling with?</label> <br />
<textarea id="message" name="message"></textarea>                                                <br />
</div>
<div>
</div>
<div>
<input type="text" name="honeypot" style="display:none">
<input type="submit" value="Submit" style="color: white; background-color: #8FBC8F; border-radius: 4px; padding: 10px 15px;"/>
</div>
</div>
</form>
<div>
