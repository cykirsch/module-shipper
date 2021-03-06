# Change Log

## 20.0.23
SHQ16-1395 remove references to carrier group factory

## 20.0.24
SHQ16-1543 belts and braces check on quote item before accessing

## 20.0.25
SHQ16-1582 display pickup location and time slot in order view
SHQ16-1682 Changed version to placeholder

## 20.0.26
SHQ16-745 eCommerce cart in request corrected

## 20.1.0
SHQ16-1619 Config flag to ignore requests if zip code blank 

## 20.1.1
SHQ16-1731 corrected function name
SHQ16-1730 resolved package helper constructor
SHQ16-1730 resolved constructor on package helper

## 20.1.2
SHQ16-1739 modify usage of checkout session, Updated issue reference in readme

## 20.1.3
SHQ16-1745 handle exception on addresses without region

## 20.1.4
SHQ16-992 implemented caching of rates using cache

## 20.1.5
Updated README with latest github issues

## 20.1.6
SHQ16-1774 record order packages

## 20.1.7
SHQ16-1708 display notification when credentials invalid in admin
SHQ16-1859 allow extension of shipper mapper functions

## 20.1.8
SHQ16-1851 removed columns from sales order grid until we find a solution

## 20.1.9
SHQ16-992 implement config switch for caching rates

## 20.2.0
SHQ16-992 implement config switch for cached rates

## 20.2.1
SHQ16-1902 use stored address type in subsequent requests

## 20.2.2
SHQ16-1922 save package detail on first pass through checkout, set carrier code when settings are shqshared
SHQ16-1927 pass store id when retrieving quote

## 20.2.3
SHQ16-1925 Resolved issue with merged rates not showing

## 20.2.4
SHQ16-594 populate shipperhq_location in request

## 20.3.0
SHQ16-1851_A reinstate order grid columns

## 20.3.1
SHQ16-1851_A reinstate order grid columns

## 20.3.2
SHQ16-1968 save packages when carrier and name is duplicated

## 20.3.3
SHQ16-2002 Fixed issue with SHQ using wrong stores API credentials within admin

## 20.3.4
SHQ16-2002 Fixed issue with SHQ using wrong stores API credentials within admin

## 20.3.5
SHQ16-2004 - custom admin shipping
SHQ16-2029 - code sniffer changes

## 20.4.0
SHQ16-2032 and SHQ16-2041 pickup date is used as start when it's today, otherwise use start date
SHQ16-2041 extended unit tests
SHQ16-2029 changes from code sniffer review

## 20.5.0
SHQ16-1967 Accessorials in M2

## 20.5.1
Corrected version number display

## 20.5.2
SHQ16-2117 resolved issue with Authorize.net and custom admin shipping

## 20.5.3
SHQ16-2123 resolve issue with install and upgrade when database has been migrated from M1 to M2

## 20.5.4
SHQ16-2123 prevent deleting default attribute group

## 20.5.5
SHQ16-2141 UPS LTL use carrier code as type

## 20.5.6
SHQ16-2154 clean up step to remove duplicates from shq order grid table

## 20.5.7
SHQ16-2159 add custom admin shipping when no rates returned

## 20.5.8
SHQ16-2171 ensure internal error message can be displayed

## 20.5.9
SHQ16-2178 prevent display of address type and validation result on front end
SHQ16-2200 Added in master packing boxes attribute to mapping

## 20.6.0
SHQ16-2178 set address type on new quote

## 20.6.1
SHQ16-2238 prevent null for city field
SHQ16-2236 class variables made public to reuse in children
SHQ16-2235 add freight attributes to catalog attributes xml
SHQ16-2219 display location selected as pickup at checkout

## 20.6.2
SHQ16-2250 add destination_type attribute if not present

## 20.7.0
SHQ16-2205 - compatibility with release candidate M2.2

## 20.7.1
SHQ16-2205 - compatibility with release candidate M2.2

## 20.7.2
SHQ16-2205 DeliveryDate column backwards compatible with 2.2 RC

## 20.7.3
SHQ16-2258 add config for backup carrier timeout

## 20.7.4
SHQ16-2281 use mutable config when getting carrier by code

## 20.7.5
SHQ16-2266 added some debug logging to assist in customer diagnosis

## 20.7.6
SHQ16-2281 use system config to enable backup carrier temporarily

## 20.7.7
SHQ16-2298 set address type when request being made from cart on logged in customer

## 20.8.0
SHQ16-2231 support for customer account carrier

## 20.8.1
SHQ16-2300 Fixed issue with deleting old carriers from config

## 20.8.2
M2-45 Ensure we check array key exists on admin order view
M2-47 Deadlocking issue work

## 20.8.3
SHQ16-2078 add unit tests for time slot calculations

## 20.8.4
M2-47 added fix to record order package items

## 20.8.5
SHQ16-2372 Fixed issue in SQL scripts

## 20.8.6
M2-51 reduce the maximum length of carrier and method code combination
SHQ16-2374 move caching of allowedMethods response to only cache if it is successful

## 20.8.7
SHQ16-2375 support for split database architecture in EE

## 20.8.8
SHQ16-2392 added comments and refactored unit tests, added tests for calendarDetails default date
M2-52 remove dependency on debug setting to enable logging

## 20.8.9
SHQ16-2346 Updated must_ship_freight with a note to say it can be overriden at carrier level

## 20.9.0
SHQ16-2417 ignore time zone when reformating dates

## 20.10.0
SHQ16-2435 Fixed issue with custom options causing a 403 error
SHQ16-2255 Support for calendar and pickup in admin orders
SHQ16-2419 Caching improvements
M2-55 Modify order recording for MAC

## 20.12.0
SHQ16-2938 option to not modify carrier, SHQ16-2434 add IP to request, SHQ16-2489 handle empty street


## 20.13.0
SHQ16-2492 modified hiding of sallowspecific field


