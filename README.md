# Kievit
<head>
link to site: https://saeesh1180.github.io/Kievit/

<script type="text/javascript">
piAId = '552312';
piCId = '92106';
piHostname = 'pi.pardot.com';

(function() {
	function async_load(){
		var s = document.createElement('script'); s.type = 'text/javascript';
		s.src = ('https:' == document.location.protocol ? 'https://pi' : 'http://cdn') + '.pardot.com/pd.js';
		var c = document.getElementsByTagName('script')[0]; c.parentNode.insertBefore(s, c);
	}
	if(window.attachEvent) { window.attachEvent('onload', async_load); }
	else { window.addEventListener('load', async_load, false); }
})();
</script>
</head>

<body>

<h2>Pardot form iframe</h2>

<iframe src="https://info.frieslandcampinaingredients.com/l/551312/2020-10-16/9l963l" width="100%" height="500" type="text/html" frameborder="0" allowTransparency="true" style="border: 0"></iframe>

<form id="fs-frm" name="registration-form" accept-charset="utf-8" action="http://info.frieslandcampinaingredients.com/l/551312/2020-11-11/9lxfkj" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="firstName">First Name</label>
    <input type="text" name="name" id="firstName" placeholder="First Name" required="">
    <label for="lastName">Last Name</label>
    <input type="text" name="name" id="lastName" placeholder="First and Last" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email" placeholder="email@domain.com- Only enter business emails" required="">
    <label for="company">Company</label>
    <input type="text" name="company" id="company" placeholder="Company name" required="">
     <label for="phoneNumber">Phone</label>
    <input type="text" name="name" id="phoneNumber" placeholder="Phone number" required="">
     <label for="phoneNumber">Country</label>
    <input type="text" name="country" id="phoneNumber" placeholder="Country" required="">
    <fieldset class="locale">
      <legend>Demographics</legend>
          <select name="state" required="">
        <option value="Select" selected="" disabled="">Region</option>
      	<option value="EMEA">EMEA</option>
      	<option value="SEAP">SEAP</option>
      	<option value="GC">Greater China</option>
      	<option value="LATAM">LATAM</option>
      	<option value="NA">NA</option>
      </select>
        <select name="state" required="">
        <option value="Select" selected="" disabled="">Segment</option>
      	<option value="Food">Food</option>
      	<option value="SEAP">Instant Sachet</option>
      	<option value="GC">Capsules</option>
      	<option value="LATAM">Foodservice drinks</option>
      	<option value="NA">All Applications</option>
      </select>
      </fieldset>
       <label for="note">Note</label>
      	<textarea rows="2" name="note" id="note" placeholder="Include any additional information"></textarea>
          <label for="company">I agree to receive information and commercial offers from FrieslandCampina.</label>
    <input type="checkbox" name="company" id="company" placeholder="Company name" required="">
      <p>FrieslandCampina processes your data in line with our privacy statement. By submitting your data, you agree to sharing your data with our carefully selected distributor in your country.</p>
    <input type="hidden" name="_subject" id="email-subject" value="Registration Form Submission">
 </fieldset>
  <input type="submit" value="Register">
</form>
</body>
