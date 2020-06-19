<style>
.thisForm{
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
    padding-bottom:10px;
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
<form class="thisForm" name="contact" method="POST" action="/thankyou" netlify>
  <div>
  <input type = "hidden" name = "form-name" value = "contact"/>
   <input type="text" class="form-control" placeholder="First Name*" id="firstName" name = "First Name" required>
  <input type="text" class="form-control" placeholder="Last Name*" id="lastName" name = "Last Name" required>
  <input type="email"class="form-control" placeholder="Email Address*" id="their_email_address" name = "Email" required>
  <input type="text" class="form-control" placeholder="Phone Number*" id="phoneNumber" name = "Phone Number" required>
  <input type="text" class="form-control" placeholder="City, State*" id="location" name = "City, State" required>
  <textarea id="message" name="message" rows="5" cols="50" class = "form-control" placeholder="Message*"></textarea>
  <button type="submit" class="btn btn-primary">Submit</button>
  </div>
</form>
</div>
