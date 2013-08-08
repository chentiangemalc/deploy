deploy
======

Software Deployment

# Table of Contents

# Team Members

* Malcolm McCaffery, Project Creator/Owner

# Overview

This project is currently in the design phase.

## Project Goal

The goal of the deploy project is to create the client and server compoenents of an enterprise class software
deployment and management solution that is: 

* free
* compact
* portable
* high performance
* simple
* reliable

It must support:

* remote software installation/removal
* hardware / software reporting
* desired configuration auditing
* desktop & mobile device management

The catalyst for developing this comes after the Project Owner's extensive experience with popular enterprise 
software management tools:

* SMS 
* SCCM (2007 & 2012)
* CA ITCM
* Altiris
* ZenWorks

Across multiple industries:

* Federal & State Government
* Airlines
* Railway
* Manufacturing
* Retail
* Logistics
* Financial Services / Banking

And finding frustration in ...

* Complex licensing schemes
* Complex software configuration (which due to complexity often gets configured wrong)
* Complex reporting
* Reliability Issues
* Large Client (100 MB +)
* Poor multi-platform support
* Costly Infrastructure requried for multi-site support
* Slow Performance

The project's goal is to elminate the above issues by :

* Server 100% Linux + MariaDB platform
* KISS approach (Keep It Simple Stupid)
* 100% Native Code (i.e. C++, avoid managed code)
* Fully documented API to create your own clients and/or server
* Support multiple sites from a single server

Initially focus on clients for Windows and MacOS, and management of Apple & Android mobile devices.

# Project Tasks

## Design Phase - Part 1

[ ] Identify what types of data will need to be stored in database
[ ] Identify storage method for software packages
[ ] Identify whst types of commands will need to be sent between client and server
[ ] Identify Default Linux Distribution for Server
[ ] Identify options for multi-site support
[ ] Identify options for iOS and Android device management

## Design Phase - Part 2

[ ] Database Schema Detailed Design
[ ] Client/Server Protocol Detailed Design
[ ] Multi-Site Support Detailed Design
[ ] Management User Interface High Level Design
[ ] Identify suitable C++ Libraries for build phase

## Build Phase - Part 1 - PoC (Alpha 0.1)

The PoC should support the following:

[ ] Create Software Package via Web Interface, importing MSI + MST
[ ] Push client to remote Windows Machine
[ ] Query hardware of remote Windows machine via Web Interface
[ ] Deploy Software Package to remote Windows Machine
[ ] Report Software Package installation success/failure + install logs via Web Interface

## Build Phase - Part 2  PoC (Alpha 0.2)

[ ] Create Software Package via Web Interface, importing MacOS Software Package
[ ] Push client to remote MacOS Machine
[ ] Query hardware of remote MacOS machine via Web interface
[ ] Deploy Software Package to remote MacOS machine
[ ] Report Software Package installtion success/failure + install logs via Web Interface

## Build Phase - Part 3 - PoC (Alpha 0.3)

[ ] Support iOS Device Management

## Build Phase - Part 4 - PoC (Alpha 0.4)

[ ] Support Android Device Management

## Build Phase - Part 5 - PoC (Alpha 0.5)

[ ] Implement multi-site support

## Review Phae (PoC)

[ ] Actively seek new project contributors to assist with project
[ ] Review PoC mplementation and develop plans and requirements for a Beta 1.0 releae.
