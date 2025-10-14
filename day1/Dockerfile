FROM python:3.12-slim

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 4242

# Example of how to start my crypto gpu renting node :)
CMD ["./startnode.sh"]

