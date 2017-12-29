---
layout: page
permalink: /software/introduction/
title: Introduction
---
The Geotab SDK (Software Development Kit) is a powerful set of tools for automating tasks and working with the data in MyGeotab. Within these documents you will find information on how to develop JavaScript and C# applications, build and integrate Add-Ins and use MyGeotab with third-party systems.

Various working examples are included in this SDK for use as a starting point with your own code e.g.:

* Display vehicle trips on third-party map (for example [Leaflet](http://leafletjs.com/) or [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/))
* Integrate an embedded MyGeotab frame in your web application (real time map, vehicle listing and more)
* Create your own web interface to import and export Geotab data

> Keep up to date with Geotab's technical updates by subscribing to our [technical bulletins](https://www.geotab.com/subscription/).

## Accessing the device’s data

The Geotab Data Feed API is a scalable, efficient and secure method to access all the device’s data.

There are three different types of data that can be requested from the API:

* LogRecords (such as position and speed)
* StatusData (readings of vehicle measurements e.g. oil temperature or acceleration)
* FaultData (fault codes and measurements reported by the engine)

The data feed service sample application allows the feed to be installed as a Windows service and run continuously in the background downloading data from the server (see [here](http://my3.geotab.com/sdk/#/dataFeed?geotabsdk=dataFeed)).

## Importing, exporting and synchronizing

Geotab has a set of pre-made applications (which include full source code) for synchronizing MyGeotab data and can be used for example to:

* Import your customer list from a [CRM](http://en.wikipedia.org/wiki/Customer_relationship_management) (Customer Relationship Management) system
* Download your vehicle maintenance records into a maintenance system (DVIR)
* Keep your routes up to date based on the day's deliveries
* Synchronize your vehicle groups based on the vehicle’s role in the company
* Track Hours of Service (HOS) for regulations compliance

You can start using these tools right now by downloading the C# examples [here](https://my3.geotab.com/sdk/dotnet.zip?geotabsdk=/dotnet.zip) and the JavaScript examples [here](https://my3.geotab.com/sdk/javascript.zip?geotabsdk=/javascript.zip).

## Automating tasks

Common tasks that you perform online using MyGeotab can all be automated using the Geotab API. You can create time-saving scripts or automated processes such as:

* When a new pick-up arrives, automate the dispatching by sending a text message to the vehicle’s Garmin through an attached GO device
* Synchronize your customer’s location with the closest vehicle when a new work order is created

## Working with Add-Ins

Geotab has developed a number of Add-In products which can be easily integrated into your MyGeotab UI. The benefits of using Add-Ins are:

* Ready availability of Add-Ins to instantly integrate into your MyGeotab. Visit the [Geotab Marketplace](http://www.geotab.com/marketplace/) and the [Developing Add-Ins](https://my3.geotab.com/sdk/default.html#/addins?geotabsdk=addins) SDK page to see the available Add-Ins
* Versatility to create your own Add-In to customize a page or button to suit your needs

## Integrating with MyGeotab

You can integrate an embedded version of MyGeotab into your own web application. This is perfect for providing a website to your customers with insight as to where their deliveries are and when they will arrive. You have control of which features appear on the embedded MyGeotab to create a seamless integration between your software and ours.

By using single sign-on authentication with the Geotab API, you have the ability to manage several options from your MyGeotab user accounts including:

* Receiving an authentication token from MyGeotab for a valid username/password
* Accepting the end user agreement on behalf of the user (this has legal implications)
* Updating a user’s password
* Adding and removing a user

Each of the MyGeotab pages has a URL (Uniform Resource Locator) associated with the page that allows that page to be embedded in your own application or linked to. This is a great way to leverage MyGeotab and make it part of your services. See [here](http://my3.geotab.com/sdk/#/urlRequests?geotabsdk=urlRequests) for more details.

## Integrating third-party tracking devices into MyGeotab

Third-party tracking devices can have their data added into the MyGeotab database. The Geotab API is used to provision and upload the devices data. Additionally, data from these devices can be used in conjunction with data collected by Geotab GO devices. Contact Geotab support to have your third-party device added (each device type will receive a unique prefix code) and contact your reseller to handle billing.

Note: There may be differences in how devices from third-party manufacturers record the data; frequency of data collection and accuracy of the device record may vary. The rich information contained in the MyGeotab reports may not be fully available. Testing of these tracking device will be required to properly integrate the data into MyGeotab.

Please refer to [Using third-party devices in MyGeotab](http://my3.geotab.com/sdk/#/otherDevice?geotabsdk=otherDevice) for further details on using your own devices with MyGeotab.