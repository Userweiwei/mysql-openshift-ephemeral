FROM registry.access.redhat.com/ubi8/ubi:8.6


WORKDIR app
RUN chmod +x mvcCustomer
EXPOSE 5000
EXPOSE 5001

CMD ["/app/mvcCustomer","--urls","http://0.0.0.0:5000"]
