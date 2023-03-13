# Week 1 — App Containerization

## Containerize Backend

### Run Python

- In the backend directory, I ran `pip3 install -r requirements.txt` to set up the environment
- I added the environment variables
```
export FRONTEND_URL="*"
export BACKEND_URL="*"
python3 -m flask run --host=0.0.0.0 --port=4567
```
- I unlocked the necessary ports on the port tab and opened the link for `4567` in my browser
- I added `/api/activities/home` at the end of the url to ensure my api endpoint was working
(journal-images/API.png)



https://4567-favourdanie-awsbootcamp-t0pmri7j1dx.ws-eu90.gitpod.io/api/activities/home