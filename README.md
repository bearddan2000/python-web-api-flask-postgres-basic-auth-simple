# python-web-api-flask-postgres-basic-auth-simple

## Description
Creates an api of `dog` for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.
Uses basic authentication.

| username | password |
-----------------------
| user | pass |

## Tech stack
- python
- flask
- postgresql

## Docker stack
- python:latest
- postgresql

## To run
`sudo ./install.sh -u`
- Endpoint
  - `curl -i localhost/dog -u user:pass`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
