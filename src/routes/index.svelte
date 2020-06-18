<style>
    @media (min-width: 480px) {
        h1 {
            font-size: 4em;
        }
    }

    .hero {
        
        color:white;
        font-size: 15px;
        font-weight:bold;
        font-family:Bookman, UWC;
    }

    .hero:after {
        
        background: #3f3b3b99;
        opacity:.7;
        content: "";
        height: 100%;
        left: 0;
        position: absolute;
        top: 0;
        width: 100%;
        z-index: -1;
    }

    .container {
        padding-right: 0px;
        padding-left: 0px;
    }


    .intro {
        text-align: center;
        padding-top:30px;
        padding-bottom:20px;
        margin-left:10%;
        margin-right:10%;
    }

    .list {
        margin: 0 auto;
        padding:9.6px;
    }

    .focus {
        color: #f5f5f5;
        text-align: center;
        padding: 20px;
        background-color: #1f1f1f !important;
        font-family:Bookman, UWC;
    }

    .focus-text {
        padding-top: 15px;
        padding-bottom:15px;
        text-align: center;
        font-family:Bookman, UWC;
    }

    .card-body {
        background-color: #f5f5f5;
        text-align: left;
        font-family:Bookman, UWC;
    }

    .card-header {
        background-color: #1f1f1f;
        color: #f5f5f5;
        text-align: center;
        font-family:Bookman, UWC;
    }

    .row {
        overflow: hidden;
        margin: 0 !important;
        width: 100%;
        padding-bottom:70px;
    }
    ul{
        margin-left:25%;
        padding-bottom:20px;
    }
    
    @media (max-width:1199px){
        .break{
            display:none;
        }
    }
    @media (min-height:950px) and (max-height:1649px){
        .hero{
            background: url(/IMG-6667.jpg);
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            margin: 0 auto;
            padding: 0.25em 0.625em;
            position: relative;
            width: 100%;
            z-index: 1;
        }
    }
    @media(max-height:949px){
        .hero{
            background: url(/IMG-6666.jpg);
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            margin: 0 auto;
            padding: 0.25em 0.625em;
            position: relative;
            width: 100%;
            z-index: 1;
        }
    }
    @media (min-height: 1650px){
        .hero{
            background: url(/IMG-6668.jpg);
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            margin: 0 auto;
            padding: 0.25em 0.625em;
            position: relative;
            width: 100%;
            z-index: 1;
        }
    }
</style>

<svelte:head>
    <title>Kerpel Law</title>
</svelte:head>

<div class="hero">
    <div class="container">
        <p class="intro">Providing strong, skilled and driven representation in divorce and family law, the Law Offices
            of
            David S. Kerpel helps<br class = "break"> you achieve your goals. Our clients benefit from our success in resolving all
            issues
            relating to family law including:</p>
        <ul>
            <li class="list">Divorce</li>
            <li class="list">Paternity</li>
            <li class="list">Allocation of Parental Responsibilities (Formerly Custody)</li>
            <li class="list">Parenting Time</li>
            <li class="list">Child Support</li>
            <li class="list">Spousal Support and Maintenance</li>
            <li class="list">Orders of Protection</li>
            <li class="list">Prenuptial Agreements</li>
        </ul>
    </div>
</div>

<div class="bg-primary">
    <h5 class="focus"><span class = "first_letter">O</span>ur <span class = "first_letter">F</span>ocus</h5>
</div>

<div class="text">
    <p class="focus-text"> Providing our clients with knowledgeable and compassionate representation. <br>We strive to
        never lose sight of your goals, and will work aggressively in the pursuit of those goals.</p>
</div>

<div class="row">
    <div class="col-sm">
        <div class="card">
            <div class="card-header">
                Timely
            </div>
            <div class="card-body">
                <p class="card-text">We pride ourselves on providing reliable and prompt service in response to your
                    needs. Emails and phone calls are returned in a timely manner. </p>
            </div>
        </div>
    </div>
    <div class="col-sm">
        <div class="card">
            <div class="card-header">
                Ethical
            </div>
            <div class="card-body">
                <p class="card-text">We look for
                    creative, efficient solutions to the litigation surrounding your case. If a problem can be resolved
                    by writing a letter or making a phone call, we attempt to avoid unnecessary attorney's fees.</p>
            </div>
        </div>
    </div>
    <div class="col-sm">
        <div class="card">
            <div class="card-header">
                Profesional
            </div>
            <div class="card-body">
                <p class="card-text">If immediate attention is needed, we are aggressive in advocating for what is best
                    for our clients.</p>
            </div>
        </div>
    </div>
</div>
