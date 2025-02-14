---
name: Green Man Lane estate 
borough: ealing
tags: ealing
location: '[51.511542,-0.325448]'
landlord: Ealing Council
developer: Real/A2Dominion
itla:
total: 464
ballot: Exempt
planning: Approved
architect: Conran and Partners
image: estates/src/images/gman3.jpg
---
![Green Man Lane estate image](src/images/gman3.jpg)

464 homes on Ealing's Green Man Lane estate are earmarked for demolition.

The Green Man Lane estate regeneration is a joint venture between Ealing Council, developer Rydon and A2Dominion housing association involving the phased demolition of the estate's 464 homes in four phases over 10 years.

Ealing Council [describes](https://www.ealing.gov.uk/info/201104/housing_regeneration/373/green_man_lane/2) the replacement social housing as 'affordable rent' tenure, which can mean anything up to 80% market rent.

![Green Man Lane estate image](src/images/gmanscreenshot.png)

In December 2016, Ealing [granted planning permission](https://pam.ealing.gov.uk/online-applications/applicationDetails.do?activeTab=summary&keyVal=ODI3M8JM09L00) for phase 3 of the regeneration. There are no publicly available section 106 agreements for the scheme so it is not possible to confirm the precise tenure of the replacement 'affordable' housing.

Phase 4 (the final phase) of the scheme was approved in January 2023. Demolition of the final phase is expected to start in 2025.

There is no information relating to a right to return for tenants or leaseholders. In any event, Ealing's [shared equity offer to leaseholders](https://ealing.cmis.uk.com/ealing/Document.ashx?czJKcaeAi5tUFL1DTL2UE4zNRBcoShgo=orv9zlc1hcwmefvl%2FzC77iPz0uNaQowGhPWmce8m8fB%2FMzqMI5BQBA%3D%3D&rUzwRPf%2BZ3zd4E7Ikn8Lyw%3D%3D=pwRE6AGJFLDNlh225F5QMaQWCtPHwdhUfCZ%2FLUQzgA2uL5jNRG4jdQ%3D%3D&mCTIbCubSFfXsDGW9IXnlg%3D%3D=hFflUdN3100%3D&kCx1AnS9%2FpWZQ40DXFvdEw%3D%3D=hFflUdN3100%3D&uJovDxwdjMPoYv%2BAJvYtyA%3D%3D=ctNJFf55vVA%3D&FgPlIEJYlotS%2BYGoBi5olA%3D%3D=NHdURQburHA%3D&d9Qjj0ag1Pd993jsyOJqFvmyB7X0CSQK=ctNJFf55vVA%3D&WGewmoAfeNR9xqBux0r1Q8Za60lavYmz=ctNJFf55vVA%3D&WGewmoAfeNQ16B2MHuCpMRKZMwaG1PaO=ctNJFf55vVA%3D) requires them to invest their personal savings and take out a mortgage if they want to take up the offer.

This was [deemed unlawful](https://www.theguardian.com/society/2016/sep/16/government-blocks-controversial-plan-to-force-out-housing-estate-residents) by the Secretary of State at the 2015 Aylesbury estate CPO inquiry and required Southwark to [amend](http://moderngov.southwarksites.com/documents/s74901/Report%20Amending%20the%20shared%20equity%20rehousing%20policy%20for%20qualifying%20homeowners%20affected%20by%20regenerati.pdf) its policy.

---

<!------------THE CODE BELOW RENDERS THE MAP - DO NOT EDIT! ---------------------------->

<div id="map" style="width: 100%; height: 400px;"></div>

<script>
  var map = L.map('map').setView({{ location }}, 13);
  L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
  maxZoom: 19,
attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
}).addTo(map);
var circle = L.circle({{ location }}, {
    color: 'red',
    fillColor: '#f03',
    fillOpacity: 0.5,
    radius: 500
}).addTo(map);
</script>

---
