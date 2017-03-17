URLRedirectorOptions
====================

## Description

This widget enables you to redirect to a URL. It is a copy from the UrlRedirector widget with additional options.

## Contributing
For more information on contributing to this repository visit [Contributing to a GitHub repository] (https://world.mendix.com/display/howto50/Contributing+to+a+GitHub+repository)

## Typical usage scenario

Redirect to a static url or a URL stored as a value in an object.

## Features and limitations
 
- Open URL in a new or current browser window 
- Control commands are: open, close, redirect
- Add additional presentation options for the window.open command
- Combine prefix URL with a dynamic URL part

## Installation

Import the widget to your project and add the widget to a dataview on a page. Configure the properties to determine how the widget will behave in your application.

## Properties


#### General

##### Data source

* *Options* - Options used in the window.open function. E.g. 'resizeable,toolbar=yes,location=yes'. Only applies if "Command" = open.
* *URL(prefix)* - URL to redirect to. (E.g. http://www.mendix.com)
* *URL Attribute* - Attribute containing a URL value to redirect to. (E.g. http://www.mendix.com, you could also combine with the prefix value and add the value '/learn' to it)
* *Command Attribute* - Attribute containing the command to handle the url. Possible command values are: 'open', 'close', 'redirect'. 'redirect' will open the url in the same page.
* *Target* - Window where the redirect URL should be opened. E.g. '_blank', '_parent'. Only applies if "Command" = open.

