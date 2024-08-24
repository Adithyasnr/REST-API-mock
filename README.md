Name : Adithya Reddy 
Company Name : CODTECH IT SOLUTIONS
ID : CT08DS6534
Duration : August 5th to September 5th 2024



A)Flask Setup:
The application is initialized with Flask and Flask-RESTful, and the database is set up using SQLAlchemy.

B)Database Model:
A VideoModel class represents the structure of the video table in the database, with fields for id, name, views, and likes.

C)Argument Parsers:

1)video_put_args: Handles arguments for creating a new video.
2)video_update_args: Handles arguments for updating an existing video.
3)Resource Fields:The resource_fields dictionary defines how the output of the model will be serialized.

D)API Endpoints:

1)GET /video/<video_id>: Fetches a video by its ID.
2)PUT /video/<video_id>: Creates a new video entry if it does not exist.
3)PATCH /video/<video_id>: Updates fields of an existing video.
4)DELETE /video/<video_id>: This method is partially defined in the code but lacks complete functionality.
