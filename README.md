# Pre-work - *TipTop Service*

**TipTop Service** is a tip calculator application for iOS.

Submitted by: **Mohammed Rashadul Islam**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [x] User can select between tip percentages by tapping different values on the segmented control and the tip value is updated accordingly

The following **optional** features are implemented:

* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] Dividing the bill across multiple people
- [ ] Rounding the bill up to the nearest digit

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/JX0aqgj.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Notes

I had a difficult time understanding which items in the storyboard should be connected to which parts of the swift file. Also, when connecting objects, I don't know if I should make it a separate function or make it an outlet. I don't seem to understand how to switch to a settings page, despite creating a button for switching views. For creating custom tip values, I am not sure where to begin, such that I would be able to change the values in the array, as well as permanently changing them on the display as well. I wanted to create functionality that woudl allow for the bill to be divided by any given number of people. Furthermore, I wanted to make a slider control the tip amount, but I am unsure of how to implement this without interfering with the segmented control. Lastly, I would like to create a toggle button that would round the total up to the nearest chosen digit, so that users would not be bothered with small change.

## License

    Copyright [2020] [Mohammed Rashadul Islam]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
