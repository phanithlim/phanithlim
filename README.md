```Dockerfile
# Using a slim python base as an example
FROM python:3.11-slim

# Metadata labels
LABEL maintainer="Phanith LIM"
LABEL current_job="Full Stack Developer"
LABEL fav_color="mlue"
LABEL interests="Machine Learning, Full Stack, NLP, STT, TTS, Mobile"

# Environment variables
ENV USER_NAME="Phanith LIM"
ENV JOB_TITLE="Full Stack Developer"

# Set working directory
WORKDIR /app

# (Add your build steps here)

CMD ["echo", "Portfolio container for Phanith LIM is running."]
```
