# REST-API-mock

Flask Setup: The application is initialized with Flask and Flask-RESTful, and the database is set up using SQLAlchemy.
Database Model: A VideoModel class represents the structure of the video table in the database, with fields for id, name, views, and likes.


Argument Parsers:
video_put_args handles arguments for creating a new video.

video_update_args handles arguments for updating an existing video.

Resource Fields: The resource_fields dictionary defines how the output of the model will be serialized.

API Endpoints:
GET /video/<video_id>: Fetches a video by its ID.
PUT /video/<video_id>: Creates a new video entry if it does not exist.
PATCH /video/<video_id>: Updates fields of an existing video.
DELETE /video/<video_id>: This method is partially defined in the code but lacks complete functionality.
