Project marrowmatrix
## Connection Test
Testing the live pipeline.git add .
git commit -m "Testing my fresh connection with an edit"
git push
Testing my fresh connection with an edit.
Voice AI assistant for Indian users speaking Hinglish.
Audio spec: 24kHz 16-bit mono PCM
One audio chunk is 960 bytes which equals 20ms
Server uses Python 3.11 plus FastAPI plus asyncio
Android uses Kotlin plus Coroutines plus Oboe NDK
Target latency is under 1500ms end to end
Rules:
Never use time.sleep always use await asyncio.sleep
Never write API keys in code always use os.getenv
All server code must be async
Use logger.info never print in server files