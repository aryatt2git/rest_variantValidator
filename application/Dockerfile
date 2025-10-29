FROM python:3.13

WORKDIR /app

COPY . .

RUN apt-get update && apt-get install -y git 

RUN pip install --upgrad e pip

RUN pip install -r requirements.txt

RUN pip install -e .

CMD ["python", "rest_api/app.py"]
