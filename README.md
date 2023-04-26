# Data Maps
## A user-friendly application that shows U.S. Census Bureau information for any location on the map.

This project aims to solve two problems: optimization and curiosity. Many map applications exist that allow users to explore how the world looks or provide limited information on specific topics. For example, the U.S. Census Bureau has several maps that show demographic data from different decades. These maps are fascinating and educational, but they have some drawbacks. They are:

- Limited in scope: They only show one piece of information at a time.
- Antiquated in design: They have slow and difficult to navigate interfaces that only work in web browsers.

This project aims to improve upon these existing applications by creating a data maps application that is:

- Comprehensive in scope: It shows all the U.S. Census Bureau information for any location on the map.
- Modern in design: It has a fast and easy to navigate interface that works on any device.

The purpose of this application is not necessarily educational or research-based. Instead, it is a simple and enjoyable way of viewing information about the world.

## Features
- A map to explore terrian and select locations
- A list of various groups of data to view, such as income, ancestry, and occupations.
- A list of dropdowns of the different sections within that group, for example income level based on education.
- A table of data specific to each section, ex. "Percentage of workers making $40,000-$60,000 with a high school degree.
- A window with descriptions of the different data groups
- The ability to save selected sets of data to one's device or email.
- Google sign in and authentication
- Cross platform with Windows, Linux, MacOS, Web, IOS, and Android

## Technologies
The project consists of a variaty of technologies chosen because of the development team's experience in them and goal to learn how to stand up a complete application with them. 
![image](https://user-images.githubusercontent.com/97993107/234724435-c38f9e59-fe41-4522-8fbd-8d074db1e967.png)
- A Python/Fast API REST API using the SQLALCHEMY ORM for database connections and retreiving data from [Google Authentication]() and the [U.S. Census Bureau API]()

