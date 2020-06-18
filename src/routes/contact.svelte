<style>
.form-group{
    text-align:center;
    background-color:#f5f5f5 !important;
    padding:0px;
    margin-bottom: 0px;
    font-family:Bookman, UWC;
}
.container{
    height:100%;
    background-color:#f5f5f5 !important;
    background-size:cover;
}
::-webkit-input-placeholder {
   text-align: center;
}

:-moz-placeholder { /* Firefox 18- */
   text-align: center;  
}

::-moz-placeholder {  /* Firefox 19+ */
   text-align: center;  
}

:-ms-input-placeholder {  
   text-align: center; 
}
.form-control{
    padding:7.5px;
}
input, textarea{ 
    text-align: center; 
    border:0px;
    background:#f5f5f5;
    background-color:#f5f5f5;
}
input:onclick{
    border:0px;
}
input:focus::placeholder, textarea:focus::placeholder {
  opacity:.3;
}

input:focus{
    outline:0px !important;
    -webkit-appearance:none;
    box-shadow: none !important;
}
input:hover, textarea:hover{
    background-color:#EBEBEB;

}

.btn{
    background-color: #f5f5f5;
    width:100%;
    color:#1f1f1f;
}

.btn:hover{
    background-color:#EBEBEB ;
    color:#1f1f1f;
}
.btn:active{
    background-color:#E0E0E0 !important;
    color:#1f1f1f !important;
}
.btn:focus{
    outline:0px !important;
    -webkit-appearance:none;
    box-shadow: none !important;
}
textarea{
    color:#1f1f1f;
    background-color:#f5f5f5;
}


</style>

<svelte:head>
    <title>Contact - Kerpel Law</title>
</svelte:head>
<div class = "container">
<form class="form-group" name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field" netlify>
  <div hidden aria-hidden="true">
    <label>
      Don’t fill this out if you're human: 
      <input name="bot-field" />
    </label>
  </div>
  <div>
   <input type="text" class="form-control" placeholder="First Name*" id="firstName" required>
  <input type="text" class="form-control" placeholder="Last Name*" id="lastName" required>
  <input type="email"class="form-control" placeholder="Email Address*" id="their_email_address" required>
  <input type="text" class="form-control" placeholder="Phone Number*" id="phoneNumber" required>
  <input type="text" class="form-control" placeholder="City, State*" id="location" required>
  <textarea id="message" name="message" rows="5" cols="50" class = "form-control" placeholder="Message*"></textarea>
    <button type="submit" class="btn btn-primary">Submit</button>
  </div>
</form>
</div>
