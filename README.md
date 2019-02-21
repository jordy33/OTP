### Getting started

WIKI [[here](https://github.com/jordy33/OTP/wiki)]

- [GTFS](https://developers.google.com/transit/gtfs/) - A GTFS feed is a group of text files that contains infrequently changing transit data, like stops, routes, trips, and other schedule data. Transit agencies typically update their GTFS feed every few months.
- [GTFS Realtime](https://developers.google.com/transit/gtfs-realtime/) - GTFS Realtime consists of three binary files that contain realtime vehicle positions, realtime arrival information, and service alerts. Transit agencies typically update these files every minute.
- [TransitFeeds](https://transitfeeds.com/) - List of GTFS/GTFS-realtime data feeds from around the world. If you're trying to get realtime data for some agency, this is a good place to start.
- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - A free, online, self-paced course for learning about GTFS and GTFS-realtime.
- [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - A series of lessons to help people utilize open transit data.

### Software for Creating APIs

Software that you can set up to provide an API to transit and multimodal data.

- [OneBusAway](http://onebusaway.org/) - A Java app that consumes GTFS and GTFS-Realtime (along with [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)) and turns them into an easy to use [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [OpenTripPlanner](http://www.opentripplanner.org/) - An open source platform for multi-modal and multi-agency journey planning, as well as returning information about a multi-modal graph (using data sources such as GTFS and [OpenStreetMap](http://www.openstreetmap.org/)).
- [TransitClock](http://thetransitclock.org) - Java application that can consume raw vehicle positions and generate prediction times in formats such as GTFS-realtime.  Formerly known as "Transitime".
- [Linked Connections](http://linkedconnections.org/) - An open-source, scalable intermodal route planning engine, which allows clients to execute the route planning algorithm (as opposed to the server). Uses GTFS data.
- [TransiCast](http://www.transicast.com/) - Provides public transportation data for North America in a single, integrated call and response format. The data is provided in stream-parsable XML and JSON formats.  Open-source on [Google Code](https://code.google.com/archive/p/rasa/).  Hosted version at www.transitcast.com [requires payment](http://www.transicast.com/coststructure.html).
- [gtfs-server](https://github.com/denysvitali/gtfs-server) - A web server, written in Rust that uses PostGIS as a backend to serve GTFS data via a HTTP endpoint
- [Navitia](https://github.com/CanalTP/navitia) is the opensource engine behind the [Navitia.io](http://www.navitia.io/) live API.
- [pyBikes](https://github.com/eskerda/pybikes) - Software powering [CityBikes](http://api.citybik.es) for worldwide bikeshare system info

### Hardware

Experimental and production transit hardware.

- [Bus Tracking GPS](https://github.com/herrdragon/busTrackingGps) - Code for Miami prototype of a cheap open-source solution to track transit buses.

### Apps

Apps people use when taking transit.

#### Web Apps

- [TransitScreen](http://transitscreen.com/) - Custom realtime displays of all local transportation choices
- [Instabus](http://instabus.org) - Realtime map of Austin's (CapMetro) public transit. Has no server/backend dependency at all and runs completely on GitHub pages.
- [Maryland MTA Real-time Vehicle Tracking](http://realtimemap.mta.maryland.gov/hiwire?.a=iRealTimeDisplay)
- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) - A Google Web Toolkit-based web interface for OpenTripPlanner
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) - A Javascript-based client for OpenTripPlanner
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - A Java-based web application for producing GTFS-realtime Service Alerts.
- [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) - HRT Bus API publishes real time bus data from Hampton Roads Transit through an application programming interface for developers to make apps from it.
- [Transit-Map](https://github.com/vasile/transit-map) - Web app that animates vehicles (markers) on a map using the public transport timetables to interpolate their positions along the routes (polylines).
- [Bikeshare Map](http://bikes.oobrien.com/) - Status of all worldwide bikeshare stations
- [Bongo](http://ebongo.org) - Real-time Transit Tracking for Iowa City, Coralville and the University of Iowa. Awesome because it combines three disparate transit systems into one UI.
- [Transitive.js](https://github.com/conveyal/transitive.js) - Creates a customizable web map layer of transit routes using Leaflet or D3.
- [Brand New Subway](http://jpwright.net/subway/) - An interactive transportation planning game that lets players alter the NYC subway system to their heart's content.
- [CityMapper Webapp](https://citymapper.com/nyc) - Really polished webapp with trip planner and route status for over 30 of cities.
- [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) - Shows shuttle arrival times for Google I/O conference, based on the open-source [transport-tracker project](https://github.com/googlemaps/transport-tracker).  Note: To implement this yourself, you need a [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/).
- [YourStop](http://yourstop.info) - Mobile friendly web app which consumes GTFS feeds and displays both live and scheduled trips for stops. Launched with MBTA, YRT/Viva and Maryland MTA.
- [1-Click](http://camsys.software/products/1-click) - A virtual “trip aggregator” that assembles information on a wide variety of available modes: public transit, private, rail, rideshare, carpool, volunteer, paratransit, and walking and biking. Open-source [on Github](https://github.com/camsys/oneclick).
- [Bustime](https://www.bustime.ru) - Public transport real-time monitoring with WebSocket updates.

#### Native Apps (open source)

- OneBusAway Apps - [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-iphone), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), [Windows 8](https://www.microsoft.com/en-us/store/apps/onebusaway/9wzdncrdm5pc) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) - An Android app for [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) - An iOS app for [OpenTripPlanner](http://www.opentripplanner.org/)
- [Transportr](https://github.com/grote/Transportr) An Android app that uses [public-transport-enabler](https://github.com/schildbach/public-transport-enabler) in order to connect to many different transport networks worldwide.
- [Offi Directions](https://gitlab.com/oeffi/oeffi) - An Android app that provides trip planning, schedules, live departure times, and disruption information for transport authorities in Europe and beyond.

#### Native Apps (closed source)

- [ally](http://www.allyapp.com/)
- [Transit](http://transitapp.com/)
- [CityMapper](https://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [Tiramisu Transit](http://www.tiramisutransit.com/)
- [TransLoc Rider](http://translocrider.com/) - Real-time transit maps for over 100 transit systems.
- [Transit Display](http://transitdisplay.com/) - Multimodal and real-time transit display software.

