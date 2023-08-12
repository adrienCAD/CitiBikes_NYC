# Citibike Lyft Station Interactive Map

![CitiBike](https://images.ctfassets.net/p6ae3zqfb1e3/5b6TOvTnqzRE6hUpe9pcPu/97a29a21836cba7e89db4e632d7f45dd/Citi_Bike_Landing_page_Hero_3x.jpg)

## Overview

This interactive map showcases Citibike Lyft stations across New York City, providing real-time information about each station's status. The map is built using JavaScript, HTML, and CSS, along with the Leaflet JavaScript library. It fetches data in real-time from the [CitiBike NY API](www.citibikenyc.com) to display the positions and statuses of stations.

![CitiBike](https://images.ctfassets.net/p6ae3zqfb1e3/3FFhNHzXA7AsVbDuVq1qBt/41ab1e92a40e5f5ec90f4a1743e3925d/Citi_Bike_ExploreNYC_Get_out_and_ride_2x.jpg)

## Features

- Display of Citibike Lyft stations across New York City.
- Markers indicate the position of each station.
- Station status is visualized through different markers and colors.
- Real-time data fetch from the CitiBike NY API.
- Basemap layer provided by OpenStreetMap.

## Station Status

The station statuses are represented by the following codes:

- `COMING_SOON`: Station is not operational yet.
- `EMPTY`: Station is empty.
- `LOW`: Station has low bike availability.
- `NORMAL`: Station has normal bike availability.
- `OUT_OF_ORDER`: Station is out of order.
- `UNDER_CONSTRUCTION`: Station is under construction.
- `WORKING_AT_CAPACITY`: Station is working at full capacity.

## Usage

1. Clone the repository.
2. Open `index.html` in your web browser.
3. Explore the interactive map to view Citibike Lyft station locations and statuses in real-time.

## Acknowledgements

- Basemap layer provided by [OpenStreetMap](https://www.openstreetmap.org/).

## Author

Adrien Caudron

Feel free to contribute, report issues, or suggest improvements to make this interactive map even better!

---

**Note**: This project is for educational purposes and is not affiliated with Citibike Lyft or any other organizations mentioned. The data displayed is fetched from the CitiBike NY API and may be subject to change.
