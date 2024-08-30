# pull python base image
FROM python:3.10
# copy application files
ADD . /titanic_model_pritika
# specify working directory
WORKDIR /titanic_model_pritika
# update pip
RUN pip install --upgrade pip
# install dependencies
# expose port for application
EXPOSE 8001
# start fastapi application
CMD ["python", "app/main.py"]
