FROM continuumio/miniconda3:latest
WORKDIR /app
COPY 1.sh .
RUN chmod +x 1.sh
RUN conda install -c conda-forge mlflow boto3 pymysql -y
CMD ["./1.sh"]
