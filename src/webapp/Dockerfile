FROM python:3.10-slim
WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY app_gradio.py .

EXPOSE 7860
CMD ["python", "app_gradio.py"]
