# CORS_Sol
How to SOLVE CORS issue??
=======================================================================================================================
Steps: 
1. take the ResponseCORSFilter.java from the repository and save it in a package in source of the web java project;
2. take the web.xml from the repository and replace the default web.xml present in your project with this web.xml.
3. In this web.xml only change those parts which are in the format  **\w_\w_\w_...** with respect to your project. The details of what to be filled over in those places are explained in the format "\w_\w_\w_..." . replace the whole  **\w_\w_\w_...** respectively.
4. thats it you are ready now.

When the restful service rendering function returns the response as "return Response.status(200).entity(responString).build();", the CORS filter is automatically called and there wont be any issue.

