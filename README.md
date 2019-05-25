# Intergalactic Pizza
Intergalactic Pizza, formerly available at http://www.igp.cx, was a school project created by Kristofer Gustafsson (info@krigu.se) and Magnus Engström (magnus@aoeu.info) in April 2000. It was a part of the database course at IT/Data at [Hulebäcksgymnasiet](http://www.hule.harryda.se)

The basic idea was to offer online pizza ordering, something that was not yet widely available at the time. To make the project more interesting, the website feature pizza ordering from any planet within the solar system. Users could either sign up to become a member of ClubIGP, a membership club that simplified the ordering process by saving delivery information, or order pizza by entering the delivery information.

Users frequently complained that no pizza was ever delivered, but the ordering process was much appreciated.

## Purpose
The purpose of the project was to show what was possible to build with the web technology at the time.

## Compatibility
Compatiblity was tested using Internet Explorer version 2, 3, 4, and 5, Netscape version 3 and 4.7, and the text based browser Lynx.

## Technology
The website was running on a Linux box with Apache, PHP3 and PostgreSQL.

The project included creative use of new technology, such as a [VRML](https://en.wikipedia.org/wiki/Vrml) world to assist in selecting what planet the pizza should be delivered to.

If the user ordered a custom pizza, with any number of custom ingredients selected from a list, an image depicting the resulting pizza would be rendered and shown to the user.

The text on the website was, at least in some parts, translatable with the localized strings stored in the database and only numerical identifiers used in the code.

Users could get the price of each pizza either in the Intergalactic Pizza currency, also known as IGP or Space Dollar, or in a number of local earth based currencies. The conversion rate between IGP and USD was fixed to 1, and the conversion rate between USD and other currencies were automatically updated from live currency information via xe.net.

## Code
The code was imported from an old backup to Github in July 2014. This repository is solely kept on Github for historical reasons. No updates or changes will ever be implemented. Please take the code for what it is.
