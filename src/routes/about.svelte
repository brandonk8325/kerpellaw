<style>
.portrait{
}
.david{
    margin-top:25%;
    width:250px;
    margin-right:50px;
}
.matt{
    width: 250px;
    margin-left:50px;
    margin-top:20%;
}
.text{
}
.matt-flex{
    margin-bottom:50px;
}
.david-flex{
    margin-top:50px;
}
.flex-container {
  display: inline-flex;
}
.flex-container > div {
   
}
p{
    text-align: justify;
    font-weight: 400;
    font-family: 'Playfair Display', serif;
    font-size:130%;
    padding:10px;
    color: #1f1f1f;
}
h6{
    text-align:center;
    font-weight:bold;
    font-size:25px;
    font-family: Bookman, UWC;
    color:#1f1f1f;
}
.container{
    background-color:#f5f5f5 !important;
    zoom:75%;
}
.period{
    font-size:0.5px;
}
.tab { 
    display:inline-block; 
    margin-left: 40px; 
}

</style>

<svelte:head>
    <title>About - Kerpel Law</title>
</svelte:head>
<div class = "container">
    <div class = "flex-container david-flex">
        <div class = "image">
            <img class = "portrait david" src = "davidkerpel.jpg" alt = "David Kerpel">
        </div>
        <div class = "text">
            <p><span class="tab"/>David Kerpel has been practicing family and matrimonial law since 1998. He is experienced in handling family law matters at every stage of the legal process. David's areas of expertise include divorce, paternity, child support and modification of child support, child custody(now known as Allocation of Parental Responsibilities), parenting time, spousal support and maintenance, prenuptial agreements, division of marital and non-marital property, and orders of protection.</p>
            <p><span class="tab"/>A skillful and accomplished attorney, David Kerpel is also a staunch advocate for children. He will work tirelessly to achieve solutions that are in the best interests of his client and the children involved
            <br><br>
            <span class="tab"/>He has worked at two of the largest matrimonial law firms in the Chicago area, before opening his own practice in 2003. David attended the University of Iowa for his undergraduate degree, and obtained his Juris Doctor from the DePaul School of Law. 
            When preparing cases for trial, David combines his knowledge and experience with his attention to detail. He is admitted to the State of Illinois Bar, and is also licensed to practice law before the U.S. District Court, Northern District of Illinois, and the United States Supreme Court.
            <br><br>
            </p>
        </div>
    </div>
    <div class = "flex-container matt-flex">
        <div class = "text">
            <p>
                <span class = "tab"/>Matthew Guthrie is a dedicated, client-focused family law attorney with over seven years of experience.
                His goal is to help clients resolve complicated family matters through honest counseling and passionate
                litigation. He specializes in navigating divorce proceedings, crafting parenting agreements, obtaining
                orders of protection, settling child support and spousal maintenance disputes, and mediating the
                division of marital property. From intake to resolution, Matthew remains a committed and
                compassionate advocate for his clients.
                <br><br><span class = "tab"/>Matthew first started practicing family law as a Judge Advocate with the United States Marine Corps.
                While running the legal aid clinic for the Marine Corps Recruit Depot in Parris Island, South Carolina,
                Matthew successfully guided military and military-dependent clients through all stages of divorce, estate
                planning, child custody, adoption, and issues regarding tax law. Most recently, Matthew worked as a
                Senior Attorney for The Northern Suburban Legal Aid Clinic where he advocated for survivors of
                domestic violence, and gained experience obtaining orders of protections for his clients. Matthew
                received his undergraduate degree from the University of Dallas, and holds a Juris Doctorate from Saint
                Mary’s University School of Law. He is admitted to the State of Illinois Bar.
            </p>
        </div>
        <div class = "image">
            <img class = "portrait matt" src = "mattguthrie_auto_x1.jpg" alt = "Matthew Guthrie">
        </div>
    </div>
</div>
<div class = "period">.</div>
