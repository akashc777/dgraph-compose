FROM dgraph/dgraph:latest

EXPOSE 8080

EXPOSE 9080

CMD ["dgraph", "alpha", "--my=alpha:7080", "--zero=zero:5080", "--security", "whitelist=0.0.0.0/0"]

