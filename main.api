from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def home():
    return {"message": "Welcome to MY API!"}

@app.get("/get-video-status")
def video_status():
    return {
        "status": "completed",
        "video_id": "12345",
        "platform": "CapCut"
    }
