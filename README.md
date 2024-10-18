

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width initial-scale=1.0"/>
    <link rel="stylesheet" href="styles.css"/>
    <script src="https://kit.fontawesome.com/672f70efcb.js" crossorigin="anonymous"></script>
    <title>memoironlineform</title>
  </head>
  <body>
    <h1 id="title">Memoir online survey form</h1>
    <p id="description"class="description"><em>we are excited for the opportunity to hold and preserve your precious memories</em></p>
<form id="survey-form">
<fieldset class="contact">
  <legend class="commentary">please fill in your contact details.</legend>

    <fieldset class="profilefile"> <legend>Upload Picture</legend>
<label class="profilepicture"><i class="fa-regular fa-user"></i><input type="file" name="profile-picture" id ="profile-picture" class="profilefile"/></label></fieldset>

<label for="name" id="name-label">please enter your names:<input required id="name" type="text" class="contactinfo" placeholder="John"></label>

<label for="other-names-label">please enter other names:<input required class="contactinfo" id="other-names-label" type="text" placeholder="Doe"></label>

<label for="email" id="email-label">please enter your email:<input id="email" required class="contactinfo" type="email" placeholder="@mail" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$"></label>

               
               
               
               <label for="phone-number">please enter your phone number:<input id="phone-number" required class="contactinfo" type="number" placeholder="+172-333-333-666"></label>


  </fieldset>

  <fieldset class="location">
     <legend>please fill in your location details.</legend>
<label for="country">What is your country of origin?</label><span style="color: black !important; display: inline; float: none;">*</span>      
        
            <select id="dropdown" name="country" class="dropdown">
                <option value="Afghanistan">Afghanistan</option>
                <option value="Åland Islands">Åland Islands</option>
                <option value="Albania">Albania</option>
                <option value="Algeria">Algeria</option>
                <option value="American Samoa">American Samoa</option>
                <option value="Andorra">Andorra</option>
                <option value="Angola">Angola</option>
                <option value="Anguilla">Anguilla</option>
                <option value="Antarctica">Antarctica</option>
                <option value="Antigua and Barbuda">Antigua and Barbuda</option>
                <option value="Argentina">Argentina</option>
                <option value="Armenia">Armenia</option>
                <option value="Aruba">Aruba</option>
                <option value="Australia">Australia</option>
                <option value="Austria">Austria</option>
                <option value="Azerbaijan">Azerbaijan</option>
                <option value="Bahamas">Bahamas</option>
                <option value="Bahrain">Bahrain</option>
                <option value="Bangladesh">Bangladesh</option>
                <option value="Barbados">Barbados</option>
                <option value="Belarus">Belarus</option>
                <option value="Belgium">Belgium</option>
                <option value="Belize">Belize</option>
                <option value="Benin">Benin</option>
                <option value="Bermuda">Bermuda</option>
                <option value="Bhutan">Bhutan</option>
                <option value="Bolivia">Bolivia</option>
                <option value="Bosnia and Herzegovina">Bosnia and Herzegovina</option>
                <option value="Botswana">Botswana</option>
                <option value="Bouvet Island">Bouvet Island</option>
                <option value="Brazil">Brazil</option>
                <option value="British Indian Ocean Territory">British Indian Ocean Territory</option>
                <option value="Brunei Darussalam">Brunei Darussalam</option>
                <option value="Bulgaria">Bulgaria</option>
                <option value="Burkina Faso">Burkina Faso</option>
                <option value="Burundi">Burundi</option>
                <option value="Cambodia">Cambodia</option>
                <option value="Cameroon">Cameroon</option>
                <option value="Canada">Canada</option>
                <option value="Cape Verde">Cape Verde</option>
                <option value="Cayman Islands">Cayman Islands</option>
                <option value="Central African Republic">Central African Republic</option>
                <option value="Chad">Chad</option>
                <option value="Chile">Chile</option>
                <option value="China">China</option>
                <option value="Christmas Island">Christmas Island</option>
                <option value="Cocos (Keeling) Islands">Cocos (Keeling) Islands</option>
                <option value="Colombia">Colombia</option>
                <option value="Comoros">Comoros</option>
                <option value="Congo">Congo</option>
                <option value="Congo, The Democratic Republic of The">Congo, The Democratic Republic of The</option>
                <option value="Cook Islands">Cook Islands</option>
                <option value="Costa Rica">Costa Rica</option>
                <option value="Cote D'ivoire">Cote D'ivoire</option>
                <option value="Croatia">Croatia</option>
                <option value="Cuba">Cuba</option>
                <option value="Cyprus">Cyprus</option>
                <option value="Czech Republic">Czech Republic</option>
                <option value="Denmark">Denmark</option>
                <option value="Djibouti">Djibouti</option>
                <option value="Dominica">Dominica</option>
                <option value="Dominican Republic">Dominican Republic</option>
                <option value="Ecuador">Ecuador</option>
                <option value="Egypt">Egypt</option>
                <option value="El Salvador">El Salvador</option>
                <option value="Equatorial Guinea">Equatorial Guinea</option>
                <option value="Eritrea">Eritrea</option>
                <option value="Estonia">Estonia</option>
                <option value="Ethiopia">Ethiopia</option>
                <option value="Falkland Islands (Malvinas)">Falkland Islands (Malvinas)</option>
                <option value="Faroe Islands">Faroe Islands</option>
                <option value="Fiji">Fiji</option>
                <option value="Finland">Finland</option>
                <option value="France">France</option>
                <option value="French Guiana">French Guiana</option>
                <option value="French Polynesia">French Polynesia</option>
                <option value="French Southern Territories">French Southern Territories</option>
                <option value="Gabon">Gabon</option>
                <option value="Gambia">Gambia</option>
                <option value="Georgia">Georgia</option>
                <option value="Germany">Germany</option>
                <option value="Ghana">Ghana</option>
                <option value="Gibraltar">Gibraltar</option>
                <option value="Greece">Greece</option>
                <option value="Greenland">Greenland</option>
                <option value="Grenada">Grenada</option>
                <option value="Guadeloupe">Guadeloupe</option>
                <option value="Guam">Guam</option>
                <option value="Guatemala">Guatemala</option>
                <option value="Guernsey">Guernsey</option>
                <option value="Guinea">Guinea</option>
                <option value="Guinea-bissau">Guinea-bissau</option>
                <option value="Guyana">Guyana</option>
                <option value="Haiti">Haiti</option>
                <option value="Heard Island and Mcdonald Islands">Heard Island and Mcdonald Islands</option>
                <option value="Holy See (Vatican City State)">Holy See (Vatican City State)</option>
                <option value="Honduras">Honduras</option>
                <option value="Hong Kong">Hong Kong</option>
                <option value="Hungary">Hungary</option>
                <option value="Iceland">Iceland</option>
                <option value="India">India</option>
                <option value="Indonesia">Indonesia</option>
                <option value="Iran, Islamic Republic of">Iran, Islamic Republic of</option>
                <option value="Iraq">Iraq</option>
                <option value="Ireland">Ireland</option>
                <option value="Isle of Man">Isle of Man</option>
                <option value="Israel">Israel</option>
                <option value="Italy">Italy</option>
                <option value="Jamaica">Jamaica</option>
                <option value="Japan">Japan</option>
                <option value="Jersey">Jersey</option>
                <option value="Jordan">Jordan</option>
                <option value="Kazakhstan">Kazakhstan</option>
                <option value="Kenya">Kenya</option>
                <option value="Kiribati">Kiribati</option>
                <option value="Korea, Democratic People's Republic of">Korea, Democratic People's Republic of</option>
                <option value="Korea, Republic of">Korea, Republic of</option>
                <option value="Kuwait">Kuwait</option>
                <option value="Kyrgyzstan">Kyrgyzstan</option>
                <option value="Lao People's Democratic Republic">Lao People's Democratic Republic</option>
                <option value="Latvia">Latvia</option>
                <option value="Lebanon">Lebanon</option>
                <option value="Lesotho">Lesotho</option>
                <option value="Liberia">Liberia</option>
                <option value="Libyan Arab Jamahiriya">Libyan Arab Jamahiriya</option>
                <option value="Liechtenstein">Liechtenstein</option>
                <option value="Lithuania">Lithuania</option>
                <option value="Luxembourg">Luxembourg</option>
                <option value="Macao">Macao</option>
                <option value="Macedonia, The Former Yugoslav Republic of">Macedonia, The Former Yugoslav Republic of</option>
                <option value="Madagascar">Madagascar</option>
                <option value="Malawi">Malawi</option>
                <option value="Malaysia">Malaysia</option>
                <option value="Maldives">Maldives</option>
                <option value="Mali">Mali</option>
                <option value="Malta">Malta</option>
                <option value="Marshall Islands">Marshall Islands</option>
                <option value="Martinique">Martinique</option>
                <option value="Mauritania">Mauritania</option>
                <option value="Mauritius">Mauritius</option>
                <option value="Mayotte">Mayotte</option>
                <option value="Mexico">Mexico</option>
                <option value="Micronesia, Federated States of">Micronesia, Federated States of</option>
                <option value="Moldova, Republic of">Moldova, Republic of</option>
                <option value="Monaco">Monaco</option>
                <option value="Mongolia">Mongolia</option>
                <option value="Montenegro">Montenegro</option>
                <option value="Montserrat">Montserrat</option>
                <option value="Morocco">Morocco</option>
                <option value="Mozambique">Mozambique</option>
                <option value="Myanmar">Myanmar</option>
                <option value="Namibia">Namibia</option>
                <option value="Nauru">Nauru</option>
                <option value="Nepal">Nepal</option>
                <option value="Netherlands">Netherlands</option>
                <option value="Netherlands Antilles">Netherlands Antilles</option>
                <option value="New Caledonia">New Caledonia</option>
                <option value="New Zealand">New Zealand</option>
                <option value="Nicaragua">Nicaragua</option>
                <option value="Niger">Niger</option>
                <option value="Nigeria">Nigeria</option>
                <option value="Niue">Niue</option>
                <option value="Norfolk Island">Norfolk Island</option>
                <option value="Northern Mariana Islands">Northern Mariana Islands</option>
                <option value="Norway">Norway</option>
                <option value="Oman">Oman</option>
                <option value="Pakistan">Pakistan</option>
                <option value="Palau">Palau</option>
                <option value="Palestinian Territory, Occupied">Palestinian Territory, Occupied</option>
                <option value="Panama">Panama</option>
                <option value="Papua New Guinea">Papua New Guinea</option>
                <option value="Paraguay">Paraguay</option>
                <option value="Peru">Peru</option>
                <option value="Philippines">Philippines</option>
                <option value="Pitcairn">Pitcairn</option>
                <option value="Poland">Poland</option>
                <option value="Portugal">Portugal</option>
                <option value="Puerto Rico">Puerto Rico</option>
                <option value="Qatar">Qatar</option>
                <option value="Reunion">Reunion</option>
                <option value="Romania">Romania</option>
                <option value="Russian Federation">Russian Federation</option>
                <option value="Rwanda">Rwanda</option>
                <option value="Saint Helena">Saint Helena</option>
                <option value="Saint Kitts and Nevis">Saint Kitts and Nevis</option>
                <option value="Saint Lucia">Saint Lucia</option>
                <option value="Saint Pierre and Miquelon">Saint Pierre and Miquelon</option>
                <option value="Saint Vincent and The Grenadines">Saint Vincent and The Grenadines</option>
                <option value="Samoa">Samoa</option>
                <option value="San Marino">San Marino</option>
                <option value="Sao Tome and Principe">Sao Tome and Principe</option>
                <option value="Saudi Arabia">Saudi Arabia</option>
                <option value="Senegal">Senegal</option>
                <option value="Serbia">Serbia</option>
                <option value="Seychelles">Seychelles</option>
                <option value="Sierra Leone">Sierra Leone</option>
                <option value="Singapore">Singapore</option>
                <option value="Slovakia">Slovakia</option>
                <option value="Slovenia">Slovenia</option>
                <option value="Solomon Islands">Solomon Islands</option>
                <option value="Somalia">Somalia</option>
                <option value="South Africa">South Africa</option>
                <option value="South Georgia and The South Sandwich Islands">South Georgia and The South Sandwich Islands</option>
                <option value="Spain">Spain</option>
                <option value="Sri Lanka">Sri Lanka</option>
                <option value="Sudan">Sudan</option>
                <option value="Suriname">Suriname</option>
                <option value="Svalbard and Jan Mayen">Svalbard and Jan Mayen</option>
                <option value="Swaziland">Swaziland</option>
                <option value="Sweden">Sweden</option>
                <option value="Switzerland">Switzerland</option>
                <option value="Syrian Arab Republic">Syrian Arab Republic</option>
                <option value="Taiwan">Taiwan</option>
                <option value="Tajikistan">Tajikistan</option>
                <option value="Tanzania, United Republic of">Tanzania, United Republic of</option>
                <option value="Thailand">Thailand</option>
                <option value="Timor-leste">Timor-leste</option>
                <option value="Togo">Togo</option>
                <option value="Tokelau">Tokelau</option>
                <option value="Tonga">Tonga</option>
                <option value="Trinidad and Tobago">Trinidad and Tobago</option>
                <option value="Tunisia">Tunisia</option>
                <option value="Turkey">Turkey</option>
                <option value="Turkmenistan">Turkmenistan</option>
                <option value="Turks and Caicos Islands">Turks and Caicos Islands</option>
                <option value="Tuvalu">Tuvalu</option>
                <option value="Uganda">Uganda</option>
                <option value="Ukraine">Ukraine</option>
                <option value="United Arab Emirates">United Arab Emirates</option>
                <option value="United Kingdom">United Kingdom</option>
                <option value="United States">United States</option>
                <option value="United States Minor Outlying Islands">United States Minor Outlying Islands</option>
                <option value="Uruguay">Uruguay</option>
                <option value="Uzbekistan">Uzbekistan</option>
                <option value="Vanuatu">Vanuatu</option>
                <option value="Venezuela">Venezuela</option>
                <option value="Viet Nam">Viet Nam</option>
                <option value="Virgin Islands, British">Virgin Islands, British</option>
                <option value="Virgin Islands, U.S.">Virgin Islands, U.S.</option>
                <option value="Wallis and Futuna">Wallis and Futuna</option>
                <option value="Western Sahara">Western Sahara</option>
                <option value="Yemen">Yemen</option>
                <option value="Zambia">Zambia</option>
                <option value="Zimbabwe">Zimbabwe</option>
            </select>

             <label for="city" class="town">which city were you born in? <input type="text" id="city" min="5" max="20" required placeholder="New York"/> </label>

            <label for="town" class="town">which town were you born in? <input type="text" id="town" min="5" max="20" required placeholder="New orleans"/> </label>

            <label class= "town" for="address"> what is your current address?     <textarea id="address" placeholder="south-east boulevard, sunshine st."></textarea> 
            </label>

  </fieldset>
<fieldset>

 <fieldset class="age">
    <legend>What is your age?</legend>

     <label for= "age"  id="number-label"><input id="number" type="number" value="age" required min="18" max="100" placeholder="23" value="age"/> kindly type in your age.</label>





</fieldset>


  <legend>Tell us more about you.</legend>

<fieldset class="progeny"><legend>If you had an account with us, who would you like to have access to view contents of your memoir account?</legend>


<label>  
                <label for= "closefriend" class="checkbox"><input id="closefriend" name="checkbox" type="checkbox" value="friend" checked/>Close friend</label>

                
                <label for= "brother" class="checkbox"><input id="brother" name="checkbox" type="checkbox" value="brother" />Brother</label>

                <label for= "sister" class="checkbox"><input id="sister" name="checkbox" type="checkbox" value="Sister" />Sister</label>
              
        <label for= "mother" class="checkbox"><input id="mother" name="checkbox" type="checkbox" value="mother" />Mother</label>

        <label for= "father" class="checkbox"><input id="father" name="checkbox" type="checkbox" value="father" />Father</label>
                
<label for= "spouse" class="checkbox"><input id="spouse" name="checkbox" type="checkbox" value="Spouse" />Spouse</label>

<label for= "son" class="checkbox"><input id="son" name="checkbox" type="checkbox" value="Son" />Son</label>
          
          <label for= "daughter" class="checkbox"><input id="daughter" name="checkbox" type="checkbox" value="Daughter" />Daughter</label>
              
              <label for= "mfamily" class="checkbox"><input id="mfamily" name="checkbox" type="checkbox" value="multiplefamily" />Multiple  family</label>

              <label for= "other" class="checkbox"><input id="other" name="checkbox" type="checkbox" value= "other" />Other</label>

              </label>
              
  
</fieldset>

</fieldset>
<fieldset class="duration">
<legend>If you had an account with us how long would you like your memoir active to remain active?</legend>

<label><input type="radio" id="radio" name="radio" required checked value="20"/>20 years</label>

<label><input type="radio" id="radio" name="radio" required checked value="40"/>40 years</label>

<label><input type="radio" id="radio" name="radio" required checked value="60" />60 years</label>

<label><input type="radio" id="radio" name="radio" required checked value="80" />80 years</label>

<label><input type="radio" id="radio" name="radio" required checked value="indefinitely"/>indefinitely</label>

</fieldset>
<fieldset class="info">
<legend>kindly provide us with some feedback</legend>

<label class="feedback" for="referrer">How did you hear about us? <select id="referrer">

  <option value="">Select one</option>
                <option value="youtube">youtube</option>
                <option value="tikok">tikok</option>
                <option value="facebook">facebook</option>
                <option value="google">google</option>
                <option value="other">other</option>

</label>
</select>


<label class ="feedback" for="feedback">What about our services could we improve? <textarea name="feedback" id="feedback" min="50" max="250"required cols="50" rows="3"></textarea>
</label>

<fieldset class="submitbutton">
<input id="submit" required class="submit" type="submit"/>
</fieldset>

</fieldset>


</form>
<p class="disclaimer"><em>kindly fill out this form truthfully, any information provided will be held privately and will not be shared publicly unless otherwise stated by you.</em></P>
  </body>
  </html>

** end of undefined **

** start of undefined **

body{
  font-family: tomahan
  width: 100%;
  height: 100vh;
  padding-bottom: 5px;
  background-image: url(https://www.hepworthlegal.com/wp-content/uploads/2016/10/What-is-a-Traditional-Family-Blog.jpg)
  
}

h1{
  font-size: 25;
  text-align: center;
  color: rgb(17, 129, 129);
 
}
.description{ 
  font-size: 13;
  text-align: center;
}
.disclaimer{
  font-size: 12;
  text-align: center;
  margin-top: -25;
  padding-bottom: 20;
  background: rgba(219, 215, 215, 0.9);

}
.profilefile{
  width: 170;
  float: right;
  font-size: 12;
  height:50;
  display: block;
  border: none
}
  
.contactinfo{
  display: block;
  width: 250;
  }
  
.town{
    display: block;
    padding-top: 10;
  }
.feedback{
  display: inline-block;
  padding: 10;
  float: right
}
.submit{
width: 200px;
height: 30px;
font-size: 20px;

}
.submitbutton{
  text-align: center;
  border: none;
  margin-bottom: -20
}
textarea[name="feedback"]{
  float: left;
  margin-top: 10;

}
.feedback{
  margin-left: -12;
  margin-top: 10
}
fieldset{
border-color: cyan transparent;
margin-top: 10
}
.fa-regular{
  width: 100
}
.checkbox{
  display: block;
  padding: 3px;

}
 .age{
   border-top: none
 } 
 .duration{
   border: none
 }
 .progeny{
   border: none

 }
 form{
   height: 1150;
   background: rgba(219, 215, 215, 0.9);
   padding: 2px;
}
input, select, textarea{
  border-color: rgba(167, 255, 255, 0.5);
  
}
 




