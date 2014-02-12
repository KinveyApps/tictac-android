## Add an App Backend

In the Kinvey console click "Add an App", enter the name "tictac" when prompted.


## Set up TicTac Project

1. Download the [TicTac](https://github.com/KinveyApps/tictac-android/archive/master.zip) project.
2. In Eclipse, go to **File &rarr; Import…**
3. Click **Android &rarr; Existing Android Code into Workspace**
4. **Browse…** to set **Root Directory** to the extracted zip from step 1
5. In the **Projects** box, make sure the **tictac** project check box is selected. Then click **Finish**.
6. Download the latest Kinvey library (zip) and extract the downloaded zip file, from: http://devcenter.kinvey.com/android/downloads
7. Copy all jars in the libs/ folder of the extracted zip to tictacs libs/ folder on the file system
8.  Download and import google support libarary v7 following the same teps listed above
9. Specify your app key and secret in `assets/kinvey.properties`

Take a look at our [Getting Started](http://devcenter.kinvey.com/android/guides/getting-started) guide for more information.


##License


Copyright (c) 2014 Kinvey Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except
in compliance with the License. You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License
is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express
or implied. See the License for the specific language governing permissions and limitations under
the License.
