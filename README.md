# SNOW-Service-Portal
![image](https://user-images.githubusercontent.com/12488769/147889536-eaf5b80f-0e9e-4cc5-85e2-d4604f2b7b14.png)

https://developer.servicenow.com/dev.do#!/learn/courses/rome/app_store_learnv2_serviceportal_rome_service_portal
![image](https://user-images.githubusercontent.com/12488769/148446642-c5b19b2f-47c3-4cdf-b118-5321fe1af1f7.png)


Service Portal Introduction Module Recap
https://developer.servicenow.com/dev.do#!/learn/courses/rome/app_store_learnv2_serviceportal_rome_service_portal/app_store_learnv2_serviceportal_rome_service_portal_introduction/app_store_learnv2_serviceportal_rome_service_portal_introduction_module_recap

Core concepts:

Service Portal is a ServiceNow framework for building portals. A portal is a user interface (UI) which provides an alternative user experience to the standard UI
The Service Portal Configuration page provides easy access to:
Branding Editor
Designer
Page Editor
Widget Editor
New Portal
Get Help
Use Page Designer to create portal pages
Portal pages are made up of:
Containers
Rows and columns
Widgets
Widget configuration options depend on widget type
Use Branding Editor to change logos and themes
Manage page responsiveness to different device types

![image](https://user-images.githubusercontent.com/12488769/148442386-2c6507b4-f03f-4251-9c25-c08e688366bd.png)


Creating Custom Widgets Module Recap
https://developer.servicenow.com/dev.do#!/learn/courses/rome/app_store_learnv2_serviceportal_rome_service_portal/app_store_learnv2_serviceportal_rome_creating_custom_widgets/app_store_learnv2_serviceportal_rome_creating_custom_widgets_module_recap
Core concepts:

Baseline widgets are read-only; to edit a baseline widget create a copy, known as a clone

The Widget Editor panes can be shown/hidden

HTML Template
CSS - SCCS
Client Script
Server Script
Link Function
Demo Data (JSON)

The Server global objects are:

data: object containing property/value pairs to send to the Client Script
input: Data object received from the Client Script's controller
options: The options used to invoke the widget on the server
The Client global objects are:

data: The serialized data object from the Server Script
options: The options used to invoke the widget on the server
The Client Script Global Functions are:

this.server.get(): Calls the Server Script and passes custom input
this.server.update(): Calls the server and posts this.data to the Server Script
this.server.refresh(): Calls the server and automatically replaces the current options and data from the server response
The Widget API includes:

spUtil (client)
spModal (client)
spAriaUtil (client)
GlideSPScriptable (server)
Test Widgets

Preview
Test Page
JavaScript console
Directives are reusable, extended HTML attributes

Defined as Angular Providers
Must be attached to a widget as a dependency
The Widget Option Schema defines user-settable options for a widget

Options are set on a widget instance basis
Options are loaded into the options object
Record Watch monitors a table for record changes which occur outside of Service Portal

![image](https://user-images.githubusercontent.com/12488769/148442405-ab0af0a6-1596-49d4-abf6-febc3dd2251e.png)


# Creating custom widgets
https://developer.servicenow.com/dev.do#!/learn/courses/rome/app_store_learnv2_serviceportal_rome_service_portal/app_store_learnv2_serviceportal_rome_creating_custom_widgets/app_store_learnv2_serviceportal_rome_widget_editor

![image](https://user-images.githubusercontent.com/12488769/148442859-87e11ad9-281f-48fa-ae17-54f9b1e6368b.png)

# Cloning Custom Widget
![image](https://user-images.githubusercontent.com/12488769/148443067-143641fa-a2bb-4bbc-a5c5-50c8c5275a35.png)

![image](https://user-images.githubusercontent.com/12488769/148443230-6902b398-1bcc-4d52-818f-de2a6523f933.png)

![image](https://user-images.githubusercontent.com/12488769/148443621-2a3de2a2-ef99-4bf8-8982-92564338b539.png)

## Previewing Widgits
![image](https://user-images.githubusercontent.com/12488769/148443988-066f4d5b-e91b-417d-90bd-a0facba6acf3.png)

![image](https://user-images.githubusercontent.com/12488769/148445348-aed981fb-d009-4b58-9612-56693aa3d551.png)
