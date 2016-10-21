#  *SmartMngrApp*
An App for Store Managers to Manage Calendar at store and department level.
**SmartMngrApp** is an android app that allows a Business/Product Owner or STORE/CLUB/NODE/DC Manager 
or Support Engineer to view store/club across the globe and to manage store/unit/department/facility level calendar details 
which are utilized to drive in-store and online customers to shop and pick up the items at specific customer pickable locations
near to them. 

Business Owners with this SmartMngrApp 
* [ ] Manage Calendar, Holidays, Events (Any store/club).
* [ ] Manage Store/Club/Department/Facility Managers
* [ ] Search and mark the store/club as prefferred one.
Product Owners with this SmartMngrApp can 
* [ ] Manage Calendar, Holidays, Events (Any store/club). 
* [ ] view Store/Club Managers
* [ ] Search and mark the store/club as prefferred one.
STORE/CLUB/NODE/DC Manager with this SmartMngrApp 
* [ ] Manage Calendar, Holidays, Events (for a given store/club).
* [ ] Manage Department/Facility Managers
* [ ] Search and mark eligible store/club as prefferred one.

The app utilizes [GSF-GlobalStoreFinder REST APIs](https://tobe.done.com/rest/public).


## User Stories

The following **required** functionality is completed:

* [ ]	User Activation and Access
  * [ ] can **activate in to SmartMngrApp** using Unique Device Auth process.
  * [ ] Wal-mart single sign on login(Optional).
* [ ] Profile based Menu's.
* [ ] ActionBar Icons and functionality
  * [ ] search nearest stores/clubs.
  * [ ] profile to view User Profile.
  * [ ] menu option to view preferred stores/clubs.
  * [ ] menu option to view Managers, perform de-activate and CRUD operations.
  * [ ] menu option to view Holidays and CRUD operations.
  * [ ] menu option to view Events and CRUD operations.
  * [ ] menu option to view and setup Settings.
* [ ] Details or Landing Page/Acitivity.
  * [ ] 3 Tab views for store/club/node/dc or department or notifications.
    * [ ] store/club/node/dc view as default view.
    * [ ] departments/facilities
    * [ ] notifications(functionality is Optional).
  * [ ] Manage store/club calendar by clicking on Image View.
  * [ ] Click on 2nd tab (departments) to view and manage their calendars.
  * [ ] Click on 3rd tab (notifications) to view and notify messages at store/deparment level.
    * [ ] User can **compose and notify** other members associated with the given store/club.
* [ ]	Business Owners **Managing Managers** 
  * [ ] can setup User(s) as a Store/Club Manager 
  * [ ] can enable/disable access. 
  * [ ] can also perform all the operations that a store manager can do.

The following **look and feel** features are implemented:

* [ ] Improve the user interface and theme the app to feel "Walmart/Sams branded"

The following **bonus** features are implemented:

* [ ] User can see embedded image media within the SmartMngrApp Views.
* [ ] User can utilize Google Map to view the search view, location etc. 

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='provide git gif url' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Picasso](http://square.github.io/picasso/) - Image loading and caching library for Android

## License

    Copyright [2016] [Wal-mart/Sams Club]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
