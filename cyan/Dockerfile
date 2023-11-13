FROM python:3.11
LABEL cyanprint.dev=true
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD python main.py
