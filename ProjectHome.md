This is a fairly simple jQuery plugin that replaces a single text input with a set of pulldown menus to select hour, minute, and am/pm. Minute selections are for quarter hours (:00, :15, :30, :45).

If the original input contains a time value in the format "hh:mmpp" (i.e., "06:30pm"), it will set the pulldown menus to the correct corresponding values. Otherwise it will default to the current time. Minute values are always rounded up to the next quarter hour.

The original input is updated whenever any of the pulldown menus change, so there is no need to change anything else in your HTML form. The plugin can be used safely to convert multiple inputs on the same page.

Options could easily be added for additional time formats or to change the minute increments (say, to every 5 minutes, for instance).

Requires jQuery <http://jquery.com>.