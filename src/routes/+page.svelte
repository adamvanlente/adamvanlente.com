<script>

    let goldenGate = "golden-gate.png";
    let currentYear = new Date().getFullYear();

</script>

<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Assistant:wght@300;400;500&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Assistant:wght@300;400&family=Playfair+Display:wght@400;500;600&display=swap" rel="stylesheet">

<header>
    <nav class="left">Adam Van Lente</nav>
    <nav class="right">
        <a href="https://github.com/adamvanlente" target="new">GitHub</a>
        <a href="https://www.linkedin.com/in/adamvanlente/" target="new">LinkedIn</a>
    </nav>
</header>


<h2>Currently</h2>
<p>CTO at <a href="https://www.crunchbase.com/organization/mikmak" target="new">MikMak</a> in NYC, where we're building an ecommerce insights platform for the world's largest brands.</p>

<h2>Previously</h2>
<p>Lead Product Engineer & Product Owner <a href="https://yieldmo.com/" target="new">Yieldmo</a>, where we built some great Applications, grew a ton, and did excellent things for mobile advertising.</p>

<h2>Before</h2>
<p>Built Geospatial software with the <a href="https://cloud.google.com/blog/products/maps-platform/open-sourcing-google-earth-enterprise" target="new">Google Maps for Business</a> team in Mountain View, and at <a href="https://www.crunchbase.com/organization/urbanmapping" target="new">Urban Mapping</a> in San Francisco.</p>

<h2>Merit</h2>
<p>I offer free 1:1 mentoring through <a href="https://www.get-merit.com/p/adam-van-lente" target="new">Merit</a>. Reach out to me there if you want to chat about navigating your role, getting promoted, or any other challenges you're facing!

</p>


<img class="golden-gate" alt="golden gate" src={goldenGate} />

<footer>&copy; {currentYear} Adam Van Lente</footer>

<style>

    header {
        font-family: 'Assistant', sans-serif;
        font-size: 18px;
        font-weight: 300;
        display: block;
        white-space: nowrap;
        padding: 8px 12px;
        margin-bottom: 12px;
    }

    nav {
        display: inline-block;
        width: 50%;
    }

    .left {
        text-align: left;
        color: rgb(224 223 223 / 99%);
    }

    .right {
        text-align: right;
    }

    .right a {
        margin-left: 12px;
    }

    a {
        text-decoration: none;
        color: #f98364;
        font-weight: 400;
    }

     
    h2,
    p {
        font-family: "Playfair Display";
        display: block;
        margin: 0 auto;
        width: 90%;
        max-width: 600px;
        font-size: 24px;
        font-weight: 400;
    }

    h2 {
        color: rgb(224 223 223 / 99%);
    }

    p {
        font-style: normal;
        margin-bottom: 24px;
    }

    .golden-gate {
        width: 140px;
        display: block;
        margin: 0 auto;
    }

    footer {
        font-family: 'Assistant', sans-serif;
        font-size: 12px;
        font-weight: 300;
        display: block;
        white-space: nowrap;
        padding: 8px 12px;
        text-align: center;
        color: rgba(156, 156, 156, 0.99);
    }

</style>