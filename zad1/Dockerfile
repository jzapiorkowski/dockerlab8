FROM python

COPY . .

RUN pip install -r requirements.txt

EXPOSE 8080

CMD ["python", "-m", "flask", "--app", "app.py", "run", "--host=0.0.0.0"]