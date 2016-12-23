# GerryPy
Geospatial Algorithm for Building Congressional Distrcits

Using data from the US census and the American Community Survey, we hope to develop criteria for a revised mapping of US congressional districts.  In the current system, the governing party in each state has the authority to draw district lanes as it pleases.  This results in the heavily diluted power of the minority party while the governing party ensures it holds as many congressional seats as possible.  We see this is a problem, and would like to provide an alternative that allows user to select criteria that will result in the recreation of district lines in a fair and balanced manner.

We will build this application using the MVC design pattern in the Pyramid framework.  We will import our datasets into a PostgreSQL database which will be accessed using PostGIS.  Using Python and GIS, we will construct district borders using an algorithm that functions according to the criteria that we specify.  The data we have has the granularity of city blocks, so each one will be addressed and assigned to a district according to its demograhpics and the demographics of its adjecent blocks.  An execution of our program will be confined to one state as these restrict the boundaries of districts.
