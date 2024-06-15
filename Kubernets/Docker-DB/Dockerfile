FROM postgres:latest
RUN echo "port = 1234" >> /etc/postgresql/postgresql.conf
CMD ["postgres", "-c", "config_file=/etc/postgresql/postgresql.conf"]

# Set environment variables
ENV POSTGRES_DB Kube
ENV POSTGRES_USER postgres
ENV POSTGRES_PASSWORD boris
EXPOSE 1234