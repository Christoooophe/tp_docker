FROM python

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "-m", "flask", "run", "--host=0.0.0.0"]