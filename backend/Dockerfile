FROM python:3-onbuild
# 'onbuild' docker image automatically installs from requirements.txt
# and expects to find our code in '/usr/src/app'
COPY . /usr/src/app
CMD ["python", "api.py"]