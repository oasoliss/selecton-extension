3.6.9
- Improve tooltip positioning over cursor
- Fix for tooltip collision detection with 'scale up' effect enabled
- Added Thai Baht currency support

3.6.8
- This update fixes issue with non-working tooltip, which affected many users in last update

3.6.7
- Add new option for drag handles style (triangle)
- Add option to shift tooltip by 'more' button's width
- More compact view for dropdowns on options page
- Fixed non working search buttons when shown in main panel
- Improve input field recognition
- Added support for RON currency

3.6.6
- Added Dutch and Traditional Chinese translations
- Updated the "support project" link to PayPal Sponsor
- Small fixes and improvements

3.6.5
- Fix for translate button text going off-screen
- Fix for Calendar button false detection (eg. '3.6.4')
- Fix for Dictionary button opening 2 tabs on click
- Fixed "what's new" button color in options to always blue

3.6.4
- Small fixes for 'Open link' and Calendar buttons
- Improved drag handle's height calculation
- Improved detection of tooltip’s side edge collision
- Improved vertical positioning of tooltip on bottom of text selection
- Added new keywords for dates and addresses
- Options page design improvements

3.6.3
- Add Calendar button for recognized dates, which opens Google Calendar on click
- Add info panel with words/symbols count, and detected language (when available)
- Add option "Hide tooltip when cursor moves away" (available when tooltip set to appear 'Over cursor')
- Add button to copy link to selected text (opens only in Chrome 90+)
- Add option for experimental vertical tooltip layout

- 'Open link' button now tries to fetch url's favicon when button icons are enabled
- Improved auto-adjusting when tooltip collapses with the screen edge
- Improved keywords recognition and overall performance
- Moved "Text fields" settings to a separate section for easier access
- Extension popup, options page and 'Test settings' page now all support browser dark mode

3.6.0
- Add option to disable tooltip arrow
- Add support for HUF and MYR currency
- Improved time conversion according to DST

3.5.9
- Fix for not showing translate button for some texts
- Add option "Left click opens link as background tab"
- Options page fixes & small design improvements

3.5.8
- Add option to display custom search options in main panel instead of hover panel
- Changed support/donate link to the new Ki-Fi page
- Small fixes and improvements

3.5.7
- Add DeepL translation option on click
- Fix for recreating tooltip when clicked on A link with active selection on page
- Fix incorrect border radius of first and last buttons
- Other small fixes

3.5.6
- Implemented test page to quickly check settings
- Added Clear button for non-empty text fields
- Added few more imperial measure units

Bug fixes:
- Fixed bug with wrong positioning in horizontal custom search options
- Fixed bug with middle click on custom search option
- Fixed wrong tooltip alignment when 'No effect' is selected
- Fixed issue with tooltip not showing up for links
(in browsers which support link selection)
- Other bug fixes & improvements

3.5.5
- Implemented new 'Highlight' button, which allows to highlight specific parts of text on page
- Implemented 'Hide exceeding buttons' option, which will hide buttons more than set in settings (defaults to 3)
- Brought back text format buttons for text fields (Bold, Italic, Strikethrough)
- Add 'Show stats on Copy button hover' and 'Show button dividers' options
- 'Open link' button now recognizes Reddit, like r/somesubreddit
- Great code refactor and performance optimization
- Added permission to run extension in iframes
- Increased extension popup height a bit
- Attempt to improve behavior on triple mouse click
- Various bug fixes and improvements

3.5.1
- Improved URL detection for 'open link' button
- Improved snapping selection by word
- Other small fixes and improvements

3.5.0
- New 'Dictionary' button, which fetches definition from Wikipedia on hover
- Improvements for 'Translate' button - live translation is now getting fetched on hover, and enabled by default
- Improved snapping text selection by words
- Improved URL detection for 'Open link' button
- Fixes for import/export functionality
- Options page improvements and fixes - expanded sections are now restored on re-open

3.4.2
- First implementation of import/export functionality
- Fix for plus sign "+" ignored by search button
- Small options page design improvements
- Add 1ms delay before applying page scripts, as attempt to fix it not being applied on some pages until reload

3.4.1
- Performance improvement - now popup should be availalbe immediately after page shows up, no need to wait for full page load
- Added browser notification on update (can be disabled in settings)
- Added config "Show translate button if language not detected" (defaults to disabled, was always enabled in prev. versions)
- Fix for popup styling not applied on some websites
- Improved handling of triple click paragraph selection
- Improved paste button behavior
- Added South Korean Won to the list of supported currencies
- Updated translations

3.4.0
- Added config "Action when click on conversion result", which now defaults to 'Copy'
- Improved keywords detection for timezones and measure units
- Improved popup appearance with button icons enabled
- Only-text email button is now consistent in style with other buttons
- Changed default animation duration config
- Performance improvements

3.3.9
- Fix wrong handles position when recreated after scroll
- Improved dark background detection - now it detects dark background behind text selection instead of whole page
- Added config "Full opacity on hover"
- Improved drag handles design a bit
- Page now gets scrolled when dragging handle to the edge of the screen
- Various small fixes and improvements

3.3.8
- Added config "Delay before reveal custom search panel"
- Added config "Disable word snapping for code"
- Added config "Floating panel when scrolled off-screen" (defaults to off)
- Excluded domains configs are no longer case-sensitive
- Fix memory leak when can't load favicons on website
- Fixed selecting with drag handle after scroll
- Fixed default Aliexpress urls
- Fix for 2GIS map search
- Added small live translate button transition
- Options page fixes and improvements
- Improved overall performance and keywords detection

3.3.7
- Fixes for live translate button
- Fixed issue when tooltip wasn't hidden on page inner scroll events

3.3.6
- Search tooltip now respects animation duration setting
- Added config "Hide translate button for user's language"
- Fix on Firefox - when clicking inside selected area recreated tooltip with no selected text anymore
- Small improvements for word snapping and drag handles
- Possible fix for currency rates not fetched sometimes

3.3.5
- Fixed dublicated Translate button issue
- Made cryptocompare.com permission explicit in manifest
- Improved dark background recognition on some websites
- Attempt to fix incompatibilities with older browsers
- Improved 'amount of icons in row' search tooltip config
- Small improvements for options page

3.3.4
- Implemented 'amount of icons in row' config
- Improved text snapping to trim some symbols in the end of selection (,:")
- Fixed performance leak when clicking inside text field
- Improved dark page detection
- Added option "Add 'Paste' button only when field is empty"
- Set higher z-index for panels for better visibility on websites
- Fixed dragging tooltip by arrow
- Added support for crypto currencies
- Small fixes and improvements

3.3.3
- Implemented new option "Invert color on dark page" + custom background color on dark pages
- Fixed issues with textfield tooltip
- Improvements for textfield handling and "Paste" button
- Fixed configs not applying for some users
- Improved word snapping algorythm
- Various small fixes and improvements

3.3.2
- Added option to apply configs immediately (no need to refresh page) - disabled by default for better performance
- Tooltip now recreates after scroll or window resize (can be disabled in settings)
- Improved "Open link" button detection (less false detections)
- Improved currency & measure units detection
- Fix for currency rates not being updated correctly
- Other small fixes and improvements

3.3.1
- Fixed bug when tooltip false-detected colliding with side edge
- Fixes for 'snap selection to words' feature and selection handles
- Small options design improvements

3.3.0
- Improved logic for drag handles
- Added new check "Don't snap selection in text fields" (defaults to "true")
- Selecton mouse listeners now won't be loaded in page unless user starts to actually select text
- Inactive custom search options are now dimmed out in settings
- Improved shifting tooltip when it collades with side edges
- Added more address markers
- Added Turkish translation
- Removed junk from code
- Changed some default configs
- Added 'Contributing' section in README
- Various performance optimizations and design improvements

3.2.7
- "Show tooltip at cursor position" now shows it on bottom of selection when multi-line + selected from top to bottom
- Selecton now can read literal multipliers for numbers on some languages (like '$5 million')
- ".00" in the end of converted price will be hidden
- Currency symbol and unit label are now colored differently than result of conversion
- Result of unit convertions is now grouped by 3 digits
- Refactored all keywords in a separate "src/data/keywords.js" file

3.2.6
- Fixed end selection handle getting placed in top left corner sometimes
- Fix for tooltip not visible when selection goes off-screen on top (when placing tooltip over cursor)
- Other small bug fixes

3.2.5
- Options page now restores previously expanded sections
- Performance & small layout improvements for options page
- Enforce background color for search options tooltip
- Changed extension name

3.2.4
- Fixed issue with tooltip not showing up on triple click
- Disabled accordeon-like animation on custom search panel reveal
- Added config to exclude domains for 'Snap selection to words' function
- Tooltip now will not be recreated when user clicks on link or button - and there's selected text somewhere else on page 

3.2.3
- Small layout fixes and improvements

3.2.2
- Fix for text field tooltip not showing up
- Text field tooltip now has 'Paste' button, when textfield is empty
- Layout fixes on some websites
- Performance improvements & security optimization

3.2.1
- Fixed issue with tooltip being dispositioned on some websites
- Tooltip now is always hidden on scroll
- Layout fixes

3.2.0
- Fixed issue with custom search options not being moved down when no space on top
- Added small outline to panels for better clarity on darker background

3.1.9
- Fixed icons being too big on some websites
- Tooltip should now be accessible immediately after main page contents loaded
- Hovered button background no longer overlaps with button separator
- Fixed border radius for first/last custom search buttons in vertical layout

3.1.8
- Added missing 'Call' icon
- Custom search options with no URL added get hidden now
- Fixed too small extension pop-up height on Firefox
- Custom search options are now horizontal by default
- Improved options page and translations

3.1.7
- Changed icons to material from Google - now all icons are better standartized in size and opacity
- Reduced extension size twice by removing old icons + improved performance
- Improved extension pop-up (it no longer has unwanted bottom padding in some browsers)

3.1.6
- Fixes for some custom search urls not working
- Implemented new option 'Horizontal alignment of tooltip'
- Disabled tooltip recreation on selection change, as it caused issues on some websites
- Improved 'move tooltip up when website has it's own' feature

3.1.5
- Tooltip now respects events when selection is changed from outside (for example by keyboard shortcut)
- Possible fix for search options tooltip being too low sometimes
- Improved selection handles logic
- Reduced CPU load
- 'Move up' is now default tooltip reveal effect
- Small layout and design improvements

3.1.4
- Fix for unit conversion not working after latest update

3.1.3
- Implemented 'Convert time' button
- Selecton is capable now of converting astrix punctuation for feet/inches (like 6'5")
- Now code to check selected text for matches will run asynchronously, which should improve overall snapiness of the tooltip
- "Live translation" button no longer breaks code to shift tooltip when colliding with side edges
- All Selecton overlays are now hidden when whole window is resized, because old dx/dy positions for them loose any sense - better solution would be to recalculate them
- Small layout fixes and improvements

3.1.1
- Snapping selection by word now is disabled when selection changed by drag handle
- Improved stability
- Added 'bold' and 'italic' buttons for input fields, which should work for inputs on all websites (only latin alphabet supported)

3.1.0
- Custom search buttons are now aligned to end when reverse buttons order enabled
- Added option to change translation service
- Small layout fixes and improvements
- Improved overall extension stability

3.0.9
- Fix for search tooltip going off-screen on top when there's no enough space
- Improvements for links detection

3.0.8
- Fix for 'Add new search button' being unaccessible for old users
- Small fixes for options and popup layout

3.0.7
- Implemented ability to change custom search engines titles
- Implemented %w placeholder for current domain (for website search)
- Fixed bug with search queries ingoring the "&" symbol
- Fix for tooltip being hidden when CTRL key is pressed to move drag handle precisely
- Fix for drag handle not adapting to magnetic selection on release
- Fix for textfield buttons borders in 'reverse buttons order' mode
- Added fallback url to fetch custom search buttons favicons

3.0.6
- Implemented live translation of selected text (up to 3 words)
- Implemented 'inverse order of the buttons' feature
- Improved number detection for currency and unit conversion
- Reduced load on resources
- Many bug fixes and improvements

3.0.5
- Fix for settings crash on first install
- Implemented 'font size' setting
- Tooltip now gets hidden on url change

3.0.4
- Added new vertical mode for custom search options
- Fix for custom search tooltip 'add new' layout bug
- Improvements for popup window design
- Refactored extension configs for better maintainability
- Custom search options settings redesigned to make it more clear that extension uses Google icons by default
- Logo became slightly sharper
- Other small fixes and improvements

3.0.3
- Fixed bugs for custom styling
- Changed default background color to a lighter one
- Added option to change currency rates update interval

3.0.2
- Changed keyboard listener so that it will less interfere with website listeners
- Small improvements for reveal animation

3.0.1
- Bug fix for custom search buttons
- Changed default URL for Wikipedia search
- Bug fix for 'move up' reveal animation - now tooltip is not interactive in first half of animation duration (when 'move up' effect is selected)


3.0.0
New:
- Implemented new "Snap selection by words" functionality (disabled while CTRL key is being held)
- Implemented 3 options for tooltip reveal animation
- Added settings toggle to override website's text selection color
- Added setting for text selection background opacity

Bug fixes and improvements:
- Middle click on any button now will open link in background tab
- Fix for Firefox "pop-up was blocked" issue on clicking Search button
- Improvements for selection handlers - single click now extends selection by one word in direction of handle

General:
- Refactored project for better readability
- New approach to horizontally center the selection tooltip between selection boundaries, instead of relying on overall selection rect
- Restructured settings page for better consistency


2.1.9
- Improvements for secondary search tooltip when 'Icon only' style is activated
- Other small improvements for 'Icon only' style
- Added support for NOK (Norwegian krone) currency
- Added ability to turn on selection handles (experimental)

2.1.8
- Fix for tooltip being moved up on some websites
- Added only-icon button style in settings + changed map icon
- Fixed bug with tooltip blinking when clicked on 'Copy' too fast
- Implemented collapsible headers in settings
- Added settings switch for debug mode
- Small bug fixes

2.1.7
- Quick fix for tooltip being invisible on some websites (such as Reddit)
- Improved moving up tooltip when website has it's own
- More UTF-8 encoding fixes (happens with Chrome on Windows)

2.1.4
- Fix moving tooltip up on some websites (Pikabu)
- Possible fix for UTF-8 encoding (Google Translate)
- Added Ukrainian translation and small translation fixes for other languages
- Various small fixes

2.1.3
- Added scale-up animation on tooltip reveal (can be disabled in settings)
- Implemented ability to disable showing unconverted value in convert buttons
- Implemented currency selection dropdown in settings
- Improved currency recognition for some currencies
- Implemented special handling for prices where coma separates fractional digits instead of thousandths
- Added Portuguese translation (from Google Translate)

2.1.2
- Implemented custom icon field for the custom search buttons
- Added 'Phone' button for phone numbers, which triggers default call handler in system on click
- Impovements for buttons appearance

2.1.1
- Layout improvements on some websites
- Implemented 'Excluded domains' option in settings for blacklisting websites
- Fixed French translation file causing extension to fail during installation
- Other small bug fixes

2.1.0
- (!) Implemented custom search buttons feature (revealed on hover over Search button)
- Added CSS color preview contextual button
- Added ability to change maps service for 'Show on map' contextual button
- Tooltip is now shifted if being open too close to the screen edge
- Fixes for 'Restore defaults' button
- Fix for 'Translate' button being added twice sometimes
- Small bug fixes and improvements

2.0.9
- Implemented email button
- Implemented 'Custom' search engine option
- Created list of currently supported currencies in README
- Updated translations

2.0.8
- Implemented button 'Show on map' (Google Maps)
- Improvements for 'open link' button

2.0.7
- Added German, French and Spanish translations (via Google Translate)
- Possible fix for bug on Jira when tickets were not open on click
- Added option to hide tooltip on key press
- Small fixes and code cleanup

2.0.6
- Fixed wrong currency rates for some currencies
- Centered arrow horizontally more precisely
- Added more search engines

2.0.5
- Added ability to change search engine
- Fixed 'Remove selection on button click' not working

2.0.4
- Implemented dynamic light/dark foreground
- Bug fixes

2.0.3
- Tooltip now gets hidden on any keystrokes
- Mouse hover always brings tooltip opacity to 1.0

2.0.1 - 2.0.2
- Bug fixes

2.0
- New extension name and icon
- Implemented textfield-specific actions (can be disabled from settings)
- Added ability to remove text selection on tooltip's button click
- Workarounds for websites that override tooltip's styling 
- Implemented ability to drag tooltip by the arrow
- Implemented ability to shift tooltip up when website has it's own selection tooltip (supports Medium and websites with similar tooltip)
- Added ability to display icons for buttons
- Implemented pop-up menu with settings
- Bug fixes and improvements

1.1.5
- Implemented default language, currency and metrics set according to browser locale
- Implemented settings to configure text selection color

1.1
- Refactored currency conversion
- Added customization options in settings
- Various bug fixes and improvements

1.0
Initial version





















