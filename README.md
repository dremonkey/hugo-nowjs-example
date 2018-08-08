# Hugo + Now Example
This is a simple Hugo app deployment on Now using the static build support.

## How it works
- standard Hugo app
- Added a simple Dockerfile which builds the app and puts the static content (and nothing else) into the `/public` directory of its own docker image
- `now.json` file created to set the type of this app as static

## Deployment

To deploy simply execute `now` from the command line.

