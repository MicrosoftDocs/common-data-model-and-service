---

title: Dynamics 365 media and communications accelerator | Microsoft Docs
description:  Develop media and communications solutions with extensions to Common Data Model. Connect to built-in forms and Dynamics 365 media and communications accelerator views.
author: MeenooRami
ms.service: common-data-model
ms.reviewer: v-dehaas
ms.topic: article
ms.date: 07/20/2020
ms.author: merami

---

# Dynamics 365 media and communications accelerator

The [Dynamics 365 media and communications accelerator](https://aka.ms/d365media) expands Common Data Model and Microsoft Power Platform into the media and entertainment industries. Version 1 of the media and communications accelerator includes data entities and attributes that center on the theme of “fan and guest engagement.” 

It includes prebuilt solutions that focus on event and venue management, sports management, ticketing and advertising sales, media sponsorships, and various guest interactions such as event registrations and the tracking of loyalty programs. The media and communications accelerator also integrates seamlessly with the Dynamics 365 Sales application and includes fields, forms, views, and dashboards.

The accelerator includes the following features:

- An extension to Common Data Model to include concepts for fan engagement, including 60-plus new entity definitions and relationships.
- Five unique model-driven applications with new forms and dashboards that support data entry and data management: 
  - Event and venue management
  - Sports management
  - Ticket sales
  - Guest management
  - Display and advertising sales
- A sample Power Portal app enables self-registration of media events which allows attendees to browse all upcoming events and sign up. This information is automatically captured and stored in your instance of the media-enhanced Common Data Model as new guest and registration entities.
- A solution that you can deploy and install from AppSource or GitHub.

## Site-map extensions

With the Dynamics 365 media and communications accelerator, institutions can optimize fan engagement, improve interactions, profile and predict actions of their customers, and gain insights from analytics. When the accelerator is installed in Dynamics 365, the experience is transformed into one specifically built for operators of theme parks, sport venues, theaters, arenas, or other places for tourism, hospitality, business conferencing, or the arts. The goal is to allow such institutions to quickly build Power Apps and Power BI visualizations.

Media and entertainment institutions can build their business processes on top of the entities in the accelerator. The ribbon customizations contain entities to record ticketing products, sponsorships, events, venues, sport teams and leagues, and more. 

## Entities and workflows

This accelerator provides these new Common Data Model entities to support the needs of media and entertainment businesses:

### Fan and guest management

- Guest
- Guest category
- External guest IDs
- Interests
- Loyalty programs and levels
- Registrations
- Promotion codes

### Event and venue management

- Venues
- Facilities
- Attractions, attraction tracks, and attraction schedules
- Concession stands and partners
- Gates
- Hours of operations
- Weather conditions
- Talent
- Media assets and asset categories

### Sports management

- League
- Team
- Player
- Player team history
- Round
- Playing field
- Conference
- Division
- Season

### Ticket sales

- Tickets
- Admissions
- Seat maps, seat tiers, seats, sections and rows

### Advertising sales

- Sponsorships
- Ad zones
- Ad segments and ad segment groups
- Ad spots
- TMAs  (Television market areas)
- Regions
- Zip codes

## Forms and dashboards

The Dynamics 365 media and communications accelerator combines standard Dynamics 365 entities with customized entities to make it easier to build solutions. This section describes some of the forms, views, and dashboards that demonstrate the new entities and the data model.

### Fan and guest management

> [!div class="mx-imgBorder"]
> ![Fan and guest management dashboard](media/media-fan-management.png "Fan and guest management dashboard")

> [!div class="mx-imgBorder"]
> ![Fan and guest management dashboard - guest screen](media/media-guest-screen.png "Fan and guest management dashboard - guest screen")

> [!div class="mx-imgBorder"]
> ![Fan and guest management dashboard - loyalty screen](media/media-loyalty-screen.png "Fan and guest management dashboard - loyalty screen")

> [!div class="mx-imgBorder"]
> ![Fan and guest management dashboard - loyalty details](media/media-loyalty-details.png "Fan and guest management dashboard - loyalty details")

The media and communications accelerator is intended to help successfully drive the progression of a customer from an anonymous or casual guest toward becoming a deeply engaged fan, regular attendee, subscribing member or active member of a frequent buyer or loyalty program. The accelerator solution helps track that journey with the addition of the new “guest” and “loyalty program” entities, which can help eventually convert to leads and then customers and contacts.

### Events and venue management

From scheduling industry events such as conferences, concerts, sporting events, and art festivals, to planning all of the attractions, rides, speakers, and concession stands within a venue (such as theme parks, museums, or tourist sites), the media data entities enable powerful ways to activate and connect data gathered from and across your entire event and venue management spectrum.

> [!div class="mx-imgBorder"]
> ![Event management dashboard](media/media-events-screen.png "Event management dashboard")

> [!div class="mx-imgBorder"]
> ![New event screen](media/media-new-event.png "New event screen")

> [!div class="mx-imgBorder"]
> ![Venue screen](media/media-venue-screen.png "Venue screen")

> [!div class="mx-imgBorder"]
> ![Venue seat map](media/media-seat-map.png "Venue seat map")

### Event registration portal

The event and registration portal allows consumers to search for upcoming media events, view their details (dates, locations, descriptions), and register to attend the event. Consumers search for events and refine their search based on event type, location, and date.

![Image of the event registration portal](media/event-registration-portal.png)


### Sports management

Key customer targets of the fan engagement scenarios within the media and communications accelerator are sports leagues, teams, and organizations that can use the accelerator to manage and schedule their seasons, games, players, referees, scorers, and other key officials. The accelerator adds a number of sports-specific data entities and relationships that enable specific use cases for the sports industry.

> [!div class="mx-imgBorder"]
> ![Sports management menu](media/media-sports-mgmt-menu.png "Sports management menu")

> [!div class="mx-imgBorder"]
> ![Sports events screen](media/media-sports-events.png "Sports events screen")


## Media product sales

### Ticketing and advertising sales

The media and communications accelerator can be used to easily build new product sales applications that help to promote, sell, and manage media-specific products like subscription services, ticketing, and advertising. New ticketing data entities include the ability to build reservations and seat management solutions through seat maps. They also enable the assignment and tracking of available and blocked seat inventory used within a venue, event, or individual attraction or conference session. That in turn allows for the monetization of individual, seasonal, or group tickets to those events. 

Similarly, you can build an application that enables the creation and sales of advertising display products. There's a key focus on  display messaging sales at a physical venue (digital billboards, scoreboards, and other signs spread across an arena or theme park). This includes the ability to specify ‘what, where, and when’ for display advertising, as well as to track and manage the sale and fulfillment of those advertisements and sponsorships.

> [!div class="mx-imgBorder"]
> ![Ticket sales dashboard](media/media-ticket-dashboard.png "Ticket sales dashboard")

> [!div class="mx-imgBorder"]
> ![Ticket sales details screen](media/media-ticket-details.png "Ticket sales details screen")

## Additional resources

- Download the Dynamics 365 media and communications accelerator from [AppSource](https://appsource.microsoft.com/marketplace/apps?search=Dynamics%20365%20Accelerator&page=1)

- The media data model, solutions, data samples, Power BI examples, SDK extensions, and more are provided as part of the open-source creative license and available on [GitHub](https://github.com/microsoft/Industry-Accelerator-Media)

- [Additional topics about the accelerators](https://aka.ms/cdmengage)

- Continue your accelerator experience and engage with experts and peers, read blog articles, and find local events within the industry accelerator community. [Join us](https://community.dynamics.com/365/industry-accelerators)

## Connect and share feedback

- Do you have feedback or need support?  [Connect with us!](https://aka.ms/cdmengage)
