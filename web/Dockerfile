FROM python
RUN pip install flask pymongo
COPY  ./static /home/devasc/ipa2025-msapp/web/static/
COPY  ./templates /home/devasc/ipa2025-msapp/web/templates/
COPY  app.py /home/devasc/ipa2025-msapp/web/
EXPOSE 8080
CMD python3 /home/devasc/ipa2025-msapp/web/app.py