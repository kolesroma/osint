# OSINT. Open source intelligence analysis
This is the concept and technology of production and use of military, political, economic and other information from open sources, without violation of laws.
The article provides basic information and tools for analysis.
```mermaid
flowchart LR
    A(OSINT) --> B1(General information)
    A(OSINT) --> B2(Technologies and tools)
     
    B1 --> GL1(<a href='https://www.rand.org/pubs/research_reports/RR1964.html'>Defining Second Generation Open Source Intelligence</a>)
    B1 --> GL2(<a href='https://www.airuniversity.af.edu/Portals/10/ASPJ_Spanish/Journals/Volume-30_Issue-2/2018_2_11_hamilton_s_eng.pdf'>The Big Data Imperative</a>)
    B1 --> GL3(<a href='https://www.frontiersin.org/research-topics/42914/open-source-intelligence-osint-threats-and-opportunities'>Threats and Opportunities</a>)
    B1 --> GL4(<a href='https://www.sciencedirect.com/topics/computer-science/open-source-intelligence'>Open Source Intelligence</a>)
    B1 --> GL5(<a href='https://www.researchgate.net/publication/340301223_Open_Source_Intelligence_OSINT_issues_and_trends'>Issues and trends</a>)

    B2 --> T1(Search engines)
    T1 --> T1L1[<a href='https://google.com'>Google</a>]
    T1 --> T1L2[<a href='https://bing.com'>Bing</a>]
    T1 --> T1L3[<a href='https://www.yahoo.com/'>Yahoo</a>]
    T1 --> T1L4[<a href='https://duckduckgo.com/'>DuckDuckGo</a>]
    T1 --> T1L5[<a href='https://yep.com/'>Yep</a>]

    B2 --> T2(Social networks)
    T2 --> T2L1[<a href='https://desktop.telegram.org'>Telegram</a>]
    T2 --> T2L2[<a href='https://twitter.com'>Twitter</a>]
    T2 --> T2L3[<a href='https://www.facebook.com'>Facebook</a>]
    T2 --> T2L4[<a href='https://www.instagram.com'>Instagram</a>]
    T2 --> T2L5[<a href='https://linkedin.com/'>LinkedIn</a>]

    B2 --> T3(Photo and video analysis)
    T3 --> T3L1[<a href='https://app.spectator.earth'>Spectator Earth</a>]
    T3 --> T3L2[<a href='https://exifdata.com'>Exifdata</a>]
    T3 --> T3L3[<a href='https://fotoforensics.com'>Camera Trace</a>]
    T3 --> T3L4[<a href='https://letsenhance.io'>LetsEnhance</a>]
    T3 --> T3L5[<a href='https://generated.photos'>Face generator</a>]
        
    B2 --> T4(Text analysis)
    T4 --> T4L1[<a href='https://tools.digitalpoint.com/cookie-search'>DP Cookie Search</a>]
    T4 --> T4L2[<a href='https://moz.com'>MOZ</a>]
    T4 --> T4L3[<a href='https://publicwww.com'>PublicWWW</a>]
    T4 --> T4L4[<a href='https://whois.domaintools.com'>Whois</a>]
    T4 --> T4L5[<a href='https://redirectdetective.com'>Redirect Detective</a>]

    B2 --> T5(Geolocation)
    T5 --> T5L1[<a href='https://www.radaratlas.com/radarspots-chrome-extension'>RadarAtlas</a>]
    T5 --> T5L2[<a href='https://mattw.io/youtube-geofind'>GeoFind</a>]          
    T5 --> T5L3[<a href='https://railradar.railyatri.in'>RailRadar GPS</a>]      
    T5 --> T5L4[<a href='https://www.windy.com'>Windy</a>]                       
    T5 --> T5L5[<a href='https://www.opentopia.com/hiddencam.php'>Opentopia</a>]  

    B2 --> T6(Transport tracking)
    T6 --> T6L1[<a href='https://www.marinetraffic.com'>Maritime Traffic Tracking</a>] 
    T6 --> T6L2[<a href='https://www.flightradar24.com'>Flight Radar 24</a>] 
    T6 --> T6L3[<a href='https://www.google.com/maps'>Google Maps Traffic</a>] 
    T6 --> T6L4[<a href='https://www.openrailwaymap.org'>Open Railway Map</a>] 
    T6 --> T6L5[<a href='https://in-the-sky.org/satmap_worldmap.php'>Live Map of Satellite Positions</a>] 

    B2 --> T7(Phone calls tracking)
    T7 --> T7L1[<a href='https://worldwidescience.org'>World Wide Science</a>]
    T7 --> T7L2[<a href='https://www.truecaller.com'>True Caller</a>]
    T7 --> T7L3[<a href='https://www.relsci.com'>Relationship Science</a>]
    T7 --> T7L4[<a href='https://mostwantedhf.info/index.php'>Mostwantedhf</a>]
    T7 --> T7L5[<a href='https://anymailfinder.com'>Anymail Finder</a>]
```