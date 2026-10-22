# Simba Coach Bus Booking

A responsive, static bus-booking site with an image-led homepage, route selection from all 47 Kenyan county headquarters and major East African destinations, route fares modeled on the displayed reference fares where available, four bus options per route, seat selection, passenger details, and a WhatsApp booking-request handoff.

## Run locally

Open `index.html` in a browser. The sample search route can be loaded with:

`index.html?from=Nairobi&to=Mombasa&date=2026-10-22&pax=1`

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose the `main` branch and `/ (root)`, then save. GitHub Pages will publish the static site.

The homepage separates Top Routes and Popular Routes and uses the supplied bus photos in randomized positions. Regional destinations include Uganda, Tanzania, Rwanda, Burundi, and South Sudan. Four bus options are listed for each route. Published route fare ranges are used where available; other fares, departure times, and seat counts are estimates and must be confirmed with the operator. Seats 1, 3, 7, 9, 10, 11, 14, 15, 18, and 20 are shown as booked in the sample seat map. Booking requests are prepared for WhatsApp number `+254733366401`; a passenger must review and send the message in WhatsApp. The contact section lists Kumasi Rd, Nairobi, Kenya and includes a Google Maps embed and directions link. No payment is processed by this static page.
