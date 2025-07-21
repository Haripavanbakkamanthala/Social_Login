Go to Google Cloud Console
Enable Google+ API and OAuth consent screen
Create new OAuth 2.0 Client ID
App Type: Web application
Authorized redirect URIs:
http://127.0.0.1:8000/accounts/google/login/callback/

Get the Client ID and Secret

Update the Client ID and Secret in google_oauth_fixture.json with your Client ID and Secret.

then run python manage.py runserver in the terminal.
