# CRUD for Yatube (api_yatube)
Based on the Yautube project(hw02-hw06)
The project contains applications and models (no frontend).
All required packages are in requirements.txt
Before starting the project, in addition to installing the virtual environment, you must run:
pip install -r equirements.txt

"api" is responsible for the logic of the project:
The API is only available to authenticated users. Token Authentication is used.
The authenticated user is authorized to change and delete their content; 
otherwise, read-only access. 
When trying to change someone else's data, a 403 Forbidden response code is returned.

In response to POST, PUT, and PATCH requests, 
the API returns an object that was added or modified.
Working with models through ModelViewSet.
