# HyzeCalendar

## Information

*Hyze is a multilayered and dynamic Calendar for iOS*

Informations and News are posted on my personal Twitter [@fforger] ( https://twitter.com/fforger )

and on Twitter [@HyzeCalendar] ( https://twitter.com/HyzeCalendar )

Website [hyze.insightmind.net] ( https://hyze.insightmind.net )


**Please post all your issues!**


## Pre-Release changelog

---

## 0.1

### 0.1.0 (19.01.2017)


* added UICollectionView and UICollectionViewCells



### 0.1.1 (22.01.2017)


* added dynamic labeling of the UICollectionViewCells by a given Month
* “NIM” = “Not in Month”



### 0.1.2 (24.01.2017)


* added MainInterface
* added daySelection
* some behind the scenes features


### 0.1.3 (25.01.2017)  


* added support for multiple Months



### 0.1.4 (27.01.2017)


* added MonthLabel
* improved UI with darkMode
* improved AutoLayout



### 0.1.5 (28.01.2017)


* added better Month capabilities
* improved UI
* added yearString to header
* fixed problems while changing color


### 0.1.6 (30.01.2017)


* improved loading duration
* improved AutoLayout
* added SectionPaging
* added jumpToToday
* added TodayButton
* smaller improvements


---

## 0.2

### 0.2.0 (02.02.2017)


* improved Colors
* new IconLogo
* new Design



### 0.2.1 (02.02.2017)


* added dayView (only some functions)
* improved loading of calendarView
* minor Bugfixes



### 0.2.2 (04.02.2017)


* added daysOfWeekLabels
* new MonthLabel
* improved loading duration (100 times faster)
* a lot of Bugfixes



### 0.2.3 (04.02.2017)


* added visual rendering of events in dayView



### 0.2.3.1 (06.02.2017)


* added guard statements to prevent the app from crashing
* added different developerModes for better debugging
* a handful of Bugfixes



### 0.2.4 (07.02.2017)


* improved jumpToToday, now with selection of todaysCell
* added cellSelectionSaving to keep selection while scrolling
* added automatic reloading of dayView
* added darkMode for dayView
* changed tabBar properties for better orientation
* added connection selectedDay in monthView to day in dayView



### 0.2.4.1 (08.02.2017)

* fixed dangerous bug




### 0.2.4.2 (11.02.2017)

* added basic EventKit implementation
* connected EventManagement to dayView




### 0.2.4.3 (11.02.2017)

* enabled rendering of allDayEvents in dayView




### 0.2.5 (12.02.2017)

* added EventKit implementation
* added EventReading from iOS Calendars
* added Conversion from event to dayViewProperties
* added rendering of events in dayView




### 0.2.6 (13.02.2017)

* improved dayView design




### 0.2.7 (13.02.2017)

* added labels for hours in dayView




### 0.2.8 (13.02.2017)

* improved dayView design


---

## 0.3

### 0.3.0 (13.02.2017)

* minor bugfixes
* prepared app for external beta testing
* EventKit implementation
* finished dayView
* improved code
* release of first betaState: preBeta



### 0.3.1 (15.02.2017)

* added settingsView
* changed navigation
* fixed bug with todaysSelection
* added toolbar
* improved overall design
* minor bugfixes


### 0.3.1.1 (15.02.2017)

* changed rendering of dayView, because of performance
* added 24hours settings to dayView
* enabled statusbar
* added new icons for labels in monthView
* dynamic icon for selectedDaybutton in monthView


### 0.3.2 (19.02.2017)

* added basic UITableView for EventsDetail
* dynamic EventsDetail when selecting a day


### 0.3.3 (20.02.2017)

* added improved UITableView for EventsDetail
* improved animations
* added information to EventsDetail
* added darkMode for EventsDetail


### 0.3.3.1 (22.02.2017)

* prevent the app from crashing
* improved visual features
* same color dayView and EventsDetail
* settings are now stored even if app is closed
* bugfixes



### 0.3.3.2 (26.02.2017)

* added preparation for next big update 0.4
* improved visualStoryboardFlow
* added static watchHand
* some minor bugfixes



### 0.3.3.3 (28.02.2017)

* major bugfixes



### 0.3.4 (28.02.2017)

* added coming soon to EditView
* added several non-functional views in EventEditor



### 0.3.5 (01.03.2017)

* added ability to add events(title, startDate, endDate)



### 0.3.6 (02.03.2017)

* added animation for eventsTableViewCellSelection
* fixed layoutBug where eventsTableViewCell was not the full screenwidth on newer iPhones



### 0.3.7 (03.03.2017)

* added animation for dayView when eventsTableViewCellSelection
* improved performance
* avoid animation when eventsTableViewCell is already selected



### 0.3.8 (21.06.2017)
  
Codename: Inception

* Completely rewritten CalendarView
* new DateCalculations
* Major performance improvements
* range of years: 4000 (year 0 to year 4000)
* added previousDays and futureDays into CalendarView
* fixed a lot of bugs in CalendarView

---

## 0.4

### 0.4 (02.08.2017)

Codename: loveAffair

* completely redesigned interface (adopt to iOS11 HIDG, more animations and shadows)
* new animateDayView toggle in Settings
* new CalendarViewLines toggle in Settings
* added automaticLayering of eventViews in the DayView
* changed renderingProcess of eventViews
* removed bottomToolbar
* improved design of EventEditor (not yet working!)
* isToday is now working correctly
* fully integrated daySelection with allDay toggle
* fixed a lot of bugs and AutoLayoutIssues
* general bugfixes and performance improvements


### 0.4.0.1 (05.08.2017)

Codename: BuggyBunny

* fixed incorrect calculations of CalendarView
* disabled 'Monday firstWeekDay', will be enabled in 0.4.0.2 (Codename: TimeShifter)
* fixed adaption of ETView while scrolling.
* fixed dayView - all Events are now shown
* new Animation in dayView, because of changes of EventViewRendering

### 0.4.0.2 (09.08.2017)

Codename: TimeShifter

* **[DESIGN]** new more distinct AppIcon
* **[USABILITY]** enhanced dayView-Animation
* **[FEATURE]** improved dayShift - Set any weekDay as firstWeekDayOfWeek


### 0.4.1

Codename: Awake

- [x] **[REQUEST]** change colorScheme or make it changeable
- [x] **[FEATURE]** add general function to add newEvents
- [x] **[FEATURE]** enabled save for DateSelection
- [x] **[FEATURE]** add NotesSection for Events
- [x] **[FEATURE]** set Date on EventEditor relativ to selected Date
- [x] **[DESIGN]** watchhand shows time dynamically
- [x] **[DESIGN]** added Red as color for Today
- [x] **[DESIGN]** CalendarViewCells now glow instead of a shadow
- [x] **[DESIGN]** changed AppIcon again
- [x] **[DESIGN]** EventEditorTitleBackgroundTransparancy
- [x] **[DESIGN]** LaunchScreen overhaul
- [x] **[USABILITY]** automatically dismiss Keyboard
- [x] **[USABILITY]** automatic reload of dayView if new Event was added
- [x] **[USABILITY]** added Locale to DateSelection and DateSelectionCell
- [x] **[CODE]** added Color to new ThemeStruct
- [x] **[CODE]** migrated code to **Swift 4**
- [x] **[BUGFIX]** automatic deselection of Cells if out of range
- [x] **[BUGFIX]** reselect Cell on reload or reappearance
- [x] **[BUGFIX]** updateETViewHeight Design when SettingsUpdate
- [x] **[BUGFIX]** make watchhand visible again
- [x] **[BUGFIX]** isToday and isSelected now works again
- [x] **[BUGFIX]** month in dayView is now correct month
- [x] **[BUGFIX]** ETView height is now correct when firstDayOfWeek is Saturday(7)
- [x] **[BUGFIX]** ETView height is now correct when month only needs 4 rows
- [x] **[BUGFIX]** no masking in EventEditorLabel


### 0.4.2

Codename: Otherside

***TESTFLIGHT_BETA***

- [x] **[REQUEST]** Notes predefined Text changed to PlaceholderText
- [x] **[REQUEST]** Swipe for nextDay
- [x] **[FEATURE]** add CalendarSelection for Settings
- [x] **[FEATURE]** add CalendarSelection for EventEditor
- [x] **[FEATURE]** add Popup for CalendarSelection
- [x] **[FEATURE]** add own localCalendar/iCloudCalendar
- [x] **[FEATURE]** add EventNonEditorView
- [x] **[FEATURE]** add possibility to Edit an Event
- [x] **[FEATURE]** remove an Event
- [x] **[FEATURE]** add Location for EventEditor
- [x] **[FEATURE]** add LocationPopover for EventEditor
- [x] **[FEATURE]** add Attendees for EventEditor
- [x] **[FEATURE]** add recurrenceRules to EventEditor
- [x] **[FEATURE]** add customRecurrenceRulePopover
- [x] **[DESIGN]** add (1)st , (2)nd, ... to midLabel in EventView
- [x] **[DESIGN]** added more shadows in EventEditor
- [x] **[CODE]** added ContactManagement
- [x] **[USABILITY]** check for sharedEvent isAdmin
- [x] **[USABILITY]** make EventEditor and EventNonEditor seamless
- [x] **[USABILITY]** automatically reload of calendarView if calendarPermission is granted
- [x] **[BUGFIX]** isAMPM EventEditor Time shows 15:00 PM
- [x] **[BUGFIX]** .deselection of EventView
- [x] **[BUGFIX]** mask of dayViewTopLabel
- [x] **[BUGFIX]** deselection of EventView even if ETViewCell is not present

### 0.4.3 (03.11.2017)

Codename: Rise

- [x] redesigned EventList
- [x] redesigned SettingsView
- [x] added watch hands
- [x] fastScrolling in calendarView
- [x] shortcut-menu for events
- [x] weekNumbers in CalendarView
- [x] alpha-Version of watchApp
- [x] added relativeEventMode for EventList
- [x] added support for iPhone 8, 8 Plus and X
- [x] reintroduced JumpToTodayButton
- [x] EventList is now draggable to 3 states
- [x] adjusted TextSize in several Areas
- [x] fixed some clipping
- [x] fixed a bug which caused crash whe creating an event
- [x] fixed fetch of locationTitle
- [x] fixed shifted weekdays in several TimeZones


... much more to come


