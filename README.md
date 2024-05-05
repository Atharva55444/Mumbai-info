<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mumbai Information</title>
    <style>
        .place-info {
            display: none;
        }
    </style>
</head>
<body>
    <h1>About Mumbai</h1>
    <p>Mumbai is a bustling metropolis on the west coast of India, known for its vibrant culture, Bollywood film industry, colonial architecture, and bustling markets. It's the capital of the Indian state of Maharashtra and is one of the largest and most populous cities in the world.</p>
    
    <h2>Areas of Mumbai</h2>
    <ul>
        <li>
            <a href="#" onclick="toggleInfo('south-mumbai')">South Mumbai (SoBo)</a>
            <div id="south-mumbai" class="place-info">
                <h3>South Mumbai (SoBo)</h3>
                <p>This area is the heart of Mumbai, known for its historical landmarks like the Gateway of India, Marine Drive, and the Taj Mahal Palace Hotel. It's also a commercial hub with many corporate offices and upscale residential neighborhoods.</p>
                <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=South+Mumbai">South Mumbai</a></p>
            </div>
        </li>
        <li>
            <a href="#" onclick="toggleInfo('bandra')">Bandra</a>
            <div id="bandra" class="place-info">
                <h3>Bandra</h3>
                <p>A trendy suburb known for its vibrant nightlife, hip cafes, and shopping streets. It's also home to many Bollywood celebrities and has a mix of residential areas and commercial establishments.</p>
                <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Bandra">Bandra</a></p>
            </div>
        </li>
        <li>
            <a href="#" onclick="toggleInfo('juhu')">Juhu</a>
            <div id="juhu" class="place-info">
                <h3>Juhu</h3>
                <p>Famous for its sprawling beach, Juhu is a popular recreational spot. It's also known for its upscale residential areas, luxury hotels, and the iconic Juhu Chaupati food stalls.</p>
                <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Juhu">Juhu</a></p>
            </div>
        </li>
        <li>
            <a href="#" onclick="toggleInfo('andheri')">Andheri</a>
            <div id="andheri" class="place-info">
                <h3>Andheri</h3>
                <p>Divided into Andheri East and Andheri West, this area is a major commercial and residential hub. It houses many corporate offices, shopping malls, restaurants, and residential complexes.</p>
                <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Andheri">Andheri</a></p>
            </div>
        </li>
        <li>
            <a href="#" onclick="toggleInfo('malad')">Malad</a>
            <div id="malad" class="place-info">
                <h3>Malad</h3>
                <p>Located in the western suburbs, Malad is a bustling area with a mix of residential and commercial spaces. It has shopping malls, entertainment centers, and a growing corporate presence.</p>
                <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Malad">Malad</a></p>
            </div>
        </li>
        <li>
            <a href="#" onclick="toggleInfo('goregaon')">Goregaon</a>
            <div id="goregaon" class="place-info">
                <h3>Goregaon</h3>
                <p>Another suburb in the western part of Mumbai, Goregaon is known for the Film City complex, which houses many Bollywood film studios. It also has residential areas, shopping malls, and recreational facilities.</p>
                <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Goregaon">Goregaon</a></p>
            </div>
        </li>
        <li>
            <a href="#" onclick="toggleInfo('powai')">Powai</a>
            <div id="powai" class="place-info">
                <h3>Powai</h3>
            <p>A suburban neighborhood known for its picturesque Powai Lake and the Powai Valley. It's also home to many multinational corporations, educational institutions, and upscale residential complexes.</p>
            <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Powai">Powai</a></p>
        </div>
    </li>
    <li>
        <a href="#" onclick="toggleInfo('borivali')">Borivali</a>
        <div id="borivali" class="place-info">
            <h3>Borivali</h3>
            <p>Located in the northern part of Mumbai, Borivali is a bustling suburb with a mix of residential areas, commercial establishments, and recreational facilities. It's known for the Sanjay Gandhi National Park, one of the largest parks in the city.</p>
            <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Borivali">Borivali</a></p>
        </div>
    </li>
    <li>
        <a href="#" onclick="toggleInfo('dadar')">Dadar</a>
        <div id="dadar" class="place-info">
            <h3>Dadar</h3>
            <p>A central neighborhood in Mumbai, Dadar is known for its bustling markets, cultural institutions, and historical landmarks. It's a major transportation hub with a railway station connecting both the central and western suburbs.</p>
            <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Dadar">Dadar</a></p>
        </div>
    </li>
    <li>
        <a href="#" onclick="toggleInfo('chembur')">Chembur</a>
        <div id="chembur" class="place-info">
            <h3>Chembur</h3>
            <p>Situated in the eastern part of Mumbai, Chembur is a predominantly residential area with pockets of commercial activity. It has good connectivity to other parts of the city and is known for its green spaces and recreational facilities.</p>
            <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Chembur">Chembur</a></p>
        </div>
    </li>
    <li>
        <a href="#" onclick="toggleInfo('colaba')">Colaba</a>
        <div id="colaba" class="place-info">
            <h3>Colaba</h3>
            <p>Located at the southern tip of Mumbai, Colaba is known for its colonial architecture, upscale hotels, and vibrant street life. It's a popular tourist destination with attractions like the Gateway of India and Colaba Causeway.</p>
            <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Colaba">Colaba</a></p>
        </div>
    </li>
    <li>
        <a href="#" onclick="toggleInfo('worli')">Worli</a>
        <div id="worli" class="place-info">
            <h3>Worli</h3>
            <p>Known for its sea-facing promenade, Worli is a mixed-use neighborhood with residential complexes, corporate offices, and commercial establishments. It's also home to the Worli Sea Link, a prominent bridge connecting the island city to the suburbs.</p>
            <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Worli">Worli</a></p>
        </div>
    </li>
    <li>
        <a href="#" onclick="toggleInfo('lower-parel')">Lower Parel</a>
        <div id="lower-parel" class="place-info">
            <h3>Lower Parel</h3>
            <p>An up-and-coming neighborhood in Mumbai, Lower Parel is known for its revitalized mill lands, trendy restaurants, and nightlife spots. It's also a major commercial hub with many corporate offices and luxury residential towers.</p>
            <p>Google Maps Location: <a href="https://www.google.com/maps/search/?api=1&query=Lower+Parel">Lower Parel</a></p>
        </div>
    </li>
</ul>

<script>
    function toggleInfo(place) {
        var info = document.getElementById(place);
        var allInfos = document.querySelectorAll('.place-info');
        allInfos.forEach(function(item) {
            if (item.id === place) {
                if (item.style.display === "none") {
                    item.style.display = "block";
                } else {
                    item.style.display = "none";
                }
            } else {
                item.style.display = "none";
            }
        });
    }
</script>
</body>
</html>
