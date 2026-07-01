# MY-APIfrom fastapi import FastAPI

# 1. Initialize your API application
app = FastAPI()

# 2. Create a "GET" endpoint (like entering a website URL)
@app.get("/")
def home():
    return {"message": "Welcome to MY API!"}

# 3. Create an endpoint that returns data
@app.get("/get-video-status")
def video_status():
    return {
        "status": "completed",
        "video_id": "12345",
        "platform": "CapCut"
    }
