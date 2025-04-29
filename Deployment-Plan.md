# Deployment Plan

## Backend Setup

- Django project packaged with Docker
- Local deployment using:
  - `docker-compose.yml`
  - `Dockerfile` with `gunicorn` and `whitenoise`

## Firebase Integration

- Firebase keys configured with `.env` variables
- Test tokens used in Postman and real devices

## Production Notes

- Although this is a course project, the system could be deployed to:
  - Heroku (free tier)
  - Railway.app
  - Render or Vercel for the frontend

## Challenges

- Local port conflicts solved via `.env` port customization
- Firebase tokens not working on iOS Simulator – used Android for real test
