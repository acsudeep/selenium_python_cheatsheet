# WebDriver class
## Properties of WebDriver class
current_url -> This gets the URL of the current page displayed in the browser.<br />
current_window_handle -> This gets the handle of the current window.<br />
name -> This gets the name of the underlying browser for this instance.<br />
orientation -> This gets the current orientation of the device.<br />
page_source -> This gets the source of the current page.<br />
title -> This gets the title of the current page.<br />
window_handles -> This gets the handles of all windows within the current session.<br />

Example: driver.current_url
<br /><br />

## Methods of the WebDriver class<br />
back() -> This goes one step backward in the browser history in the current session.<br />
close() -> This closes the current browser window.<br />
forward() -> This goes one step forward in the browser history in the current session.<br />
get(url) -> This navigates and loads a web page in the current browser session.<br />
maximize_windows() -> This maximizes the current browser window.<br />
quit() -> THis quits the driver and closes all the associated windows.<br />
refresh() -> This refreshes the current page displayed in the browser.<br />
switch_to.active_element() -> This returns the element with focus or the body if nothing else has focus.<br />
switch.to_alert() -> This switches the focus to an alret on the page.<br />
switch_to.default_content() -> This switches the focus to the default frame.<br />
switch_to.frame(frame_reference) -> This switches the focus to the specified frame, bu index, name, or web-element. This method also works on IFRAMES.<br />
switch_to.windows(window_name) -> This swtiches focus to the specifies window.<br />
implicitly_wait(time_to_wait) -> This sets a sticky timeout to implicitly wait for an element to be found, or a command to complete. This method only needs to be called one time per session. To set the timeout for calls to execute_async_script, see set_script_timeout.<br />
set_page_load_timeout(time_to_wait) -> This sets the amount of time to wait for a page load to complete.<br />
set_script_timeout(time_to_wait) -> This sets the amount of time that the script should wait during an execute_async_script call before throwing an error.<br />

Example: driver.set_script_timeout(30)
<br /><br />

# WebElement class
## Properties of the WebElement class
size -> This gets the size of the element.<br />
tag_name -> This gets this element's HTML tag name.<br />
text -> This gets the text of the element.<br />
<br />
## Methods of the WebElement class<br />
clear() -> This cleaars the content of the textbox or text area element.<br />
click() -> This clicks the element.<br />
get_attribute(name) -> This gets the attribute value from the element.<br />
is_displayed() ->This chcecks whether the element is visible to the user.<br />
is_enabled() -> This checks whether the element is enabled.<br />
is_selected() -> This checks whether the element is selected. This method is used to check the selection of a radio button or checkbox.<br />
send_keys(*value) -> This simulated typing into the element.<br />
submit() -> This submits a form. If you call this method on the element, it will submit the parent form.<br />
value_of_css_property(property_name) -> This gets the value of a CSS property.<br />


# Select class
## Properties of the Select class
all_selected_options -> This gets a list of all the selected options beloging to the dropdown or list.<br />
first_selected_option -> This gets the first selected/currently selected option from the dropdown or list.<br />
options -> This gets a list of all options from the dropdown or list.<br />

## Methods of the Select class
deselect_all() -> This clears all the selected entries from a multiselect dropdown or list.<br />
deselect_by_index(index) -> This deselects the option at the given index from the dropdown or list.<br />
deselect_bu_value(value) -> This deselects all options that have a value matching the argument from the dropdown or list.<br />
deselect_by_visible_text(text) -> This deselects all the options that display text matching the argument from the dropdown or list.<br />
select_by_index(index) -> This selects an option at the given index from the dropdown or list.<br />
select_by_value(value) -> This selects all the options that have a value matching the argument from the dropdown or list.<br />
select_by_visible_text(text) -> This selects all the options that display the text matching the argument from the dropdown or list.<br />

# Alert class
## Properties of the Alert class
text -> This gets text from the alert window<br />

## Methods of the ALert class
accept() -> This will accept the JavaScript alert box that is click on the OK button.<br />
dismiss() -> This will dismiss the JavaScript alert box that is click on the Cancel button.<br />
send_keys(*value) -> This simulates typing into the element.<br />


<br />
<br />
<br />
Reference: <br />
Learning Selenium Testing Tools with Python, Unmesh Gundecha