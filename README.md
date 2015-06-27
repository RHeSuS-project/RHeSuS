# RHeSuS
## Warning
I'm currently performing a full rewrite of the project. I just decided to publish our (ancient) Proof of concept. Help and suggenstions are appreciated.

# What is RHeSuS

RHeSuS is a high performance, component-based Statistical pattern recognition system for Structural Health Monitoring using time series modeling. It's mainly designed with with wearable technology in mind. The name RHeSuS is an equivoque for the "Rh blood group system". It can also be thought of as an abreviation for "Realtime Health Surveillance System".

## What is RHeSuS Best for?

RHeSuS is a generic monitoring system, meaning that it can be used for creating all kinds of health monitoring systems. Because of its component-based architecture and sophisticated caching support, it is especially suitable for building large-scale systems for hospitals, fitness centra, retirement homes, military, and so on.

## How does RHeSuS Compare with Other Statistical pattern recognition systems?

If you're already familiar with Statistical pattern recognition systems, you may appreciate knowing how RHeSuS compares:
* RHeSuS takes the philosophy that code should be written in a simple yet elegant way. RHeSuS will never try to over-design things mainly for the purpose of strictly following some design pattern.
* RHeSuS is extremely extensible. You can customize or replace nearly every piece of the core's code. You can also take advantage of RHeSuS's solid extension architecture to use or develop redistributable extensions.
* High performance is always a primary goal of RHeSuS.
* RHeSuS is adopting the latest technologies and protocols, including Composer, PSR, namespaces, traits, and so forth.

Rhesus Consists of 3 main components: 
* The Service
* The agent
* The interface

h3. The service

The RHeSuS service is a RESTfull interface on which you can link any kind of application.
* The RHeSuS service, like most PHP systems, implements the MVC (Model-View-Controller) design pattern and promotes code organization based on that pattern.
* Because the RHeSuS Service is PHP, you can host it on any kind of web hosting, PC or server.
* RHeSuS requires PHP 5.4.0 or above. You can find more detailed requirements for individual features by running the requirement checker included in every RHeSuS release.

### The agent

The Rhesus agent is a cross platform mobile app that can monitor any BLE or ANT+ device.
* It's mainly built with high performance and low energy consumption in mind.
* The RHeSuS agent buffers the information and, when connected, it sends the monitored information to the service in a compressed manner.

### The client

The RHeSuS client is a browser based analytics and search dashboard for the RHeSuS service. RHeSuS is a snap to setup and start using. Written entirely in HTML and Javascript it requires only a plain webserver, the client requires no fancy server side components. The RHeSuS client strives to be easy to get started with, while also being flexible and powerful.

### Contributors

RHeSuS is not a one-man show, it is backed up by a strong core developer team, as well as a community of professionals constantly contributing to RHeSuS's development. The RHeSuS developer team keeps a close eye on the latest Web development trends and on the best practices and features found in other projects. The most relevant best practices and features found elsewhere are regularly incorporated into the core framework and exposed via simple and elegant interfaces. It is also not written from scratch. Rhesus incorporates, and owes its existence to many other open source frameworks and libraries.


Programming in RHeSuS requires at least basic knowledge of object-oriented programming (OOP), NodeJS and PHP. Understanding these concepts will help you more easily pick up RHeSuS.
