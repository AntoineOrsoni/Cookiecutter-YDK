FROM ydkdev/ydk-py
COPY ./myapp /root/myapp/
WORKDIR /root/myapp/
RUN pip3 install -r requirements.txt
CMD python3 -i {{cookiecutter.main}}.py