{\rtf1\ansi\ansicpg1252\cocoartf1404\cocoasubrtf460
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \
\
To add new pages to the project, I have\
\
1. Created a new page in the containers (app/containers/ProductListing.jsx). This page is used as the UI. This returns Productlisting\
2. Added a link in the Navigation.jsx (package: app/containers). This adds \'93Product list\'94 menu navigation bar. We need to define what the path is going to be when user performs a click action (/ProductListing)\
3. We need to define a route for this path (/ProductListing). We need to edit the app/routes.jsx. \
    a. import the container using \'93import Productlisting from 'containers/ProductListing\'92;\'94\
    b. Used the route tag to define the mapping for path to the component\
}