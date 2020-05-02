FROM ydkdev/ydk-py
COPY ./{{cookiecutter.myapp_dir}} /root/{{cookiecutter.myapp_dir}}/
WORKDIR /root/{{cookiecutter.myapp_dir}}/
RUN pip3 install -r requirements.txt
CMD python3 -i {{cookiecutter.main}}.py