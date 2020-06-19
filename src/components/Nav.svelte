<script>
    export let segment;

    const handleClick = () => alert('I warned you!');
</script>

<style>
    .header {
        padding: 3rem 3rem 0;
        width: 100%;
        
    }
    .header_info{
        font-family: Bookman, URW !important;
        text-transform: none;
        letter-spacing: 1px;
        padding-bottom:10px;
    }
    .header_text{
        font-size:25px;
        font-family: Bookman, URW !important;
    }
    .header_text::first-letter, .first_letter{
        font-size: 35px !important;
    }

    .header h1 {
        margin: 0;
    }

    .navbar-brand {
        margin: 0;
    }

    .nav-item {
        margin: 0 1rem;
        text-align: center;
    }

    .text-light {
        color: #f5f5f5 !important;
    }

    .navbar-dark, .big-primary, .header, .main {
        background-color: #1f1f1f !important;
    }

    .text-medium {
        color: #1f1f1f;
    }

    h3 {
        font-size: 15px;
        padding-top: 7px;
    }
    nav{
        padding:5px !important;
    }    
    .nav-link, .navbar-brand{
        font-family:bookman, UWC;
    }    
</style>
<div class="header bg-primary d-inline-block">
    <h1 class="text-light text-center header_text">Law <span class = "first_letter">O</span>ffices <span class = "first_letter">o</span>f <span class = "first_letter">D</span>avid <span class = "first_letter">S</span>. <span class = "first_letter">K</span>erpel, <span class = "first_letter">LLC</span></h1>
    <h3 class="text-medium text-center text-light header_info">Matrimonial and Family Law Representation for Clients in Northern
        Illinois, Lake and Cook Counties</h3>
</div>
<nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-primary">
    <div class="container">
        <p class="d-sm-block d-md-none navbar-brand">{segment||"Home"}</p>

        <button class="navbar-toggler collapsed" type="button" data-toggle="collapse" data-target="#navbarColor01"
                aria-controls="navbarColor01" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="navbar-collapse collapse" id="navbarColor01" style="">
            <ul class="navbar-nav m-auto">
                <li class={`nav-item ${segment===undefined && "active"}`}>
                    <a class="nav-link" href="/">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class={`nav-item ${segment==="about" && "active"}`}>
                    <a class="nav-link" href="about">About</a>
                </li>
                <li class={`nav-item ${segment==="articles" && "active"}`}>
                    <a class="nav-link" href="articles">Articles</a>
                </li>
                <li class={`nav-item ${segment==="FAQ" && "active"}`}>
                    <a class="nav-link" href="FAQ">FAQ</a>
                </li>
                <li class={`nav-item ${segment==="resources" && "active"}`}>
                    <a class="nav-link" href="resources">Resources</a>
                </li>
                <li class={`nav-item ${segment==="reviews" && "active"}`}>
                    <a class="nav-link" href="reviews">Reviews</a>
                </li>
                <li class={`nav-item ${segment==="contact" && "active"}`}>
                    <a class="nav-link" href="contact">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
