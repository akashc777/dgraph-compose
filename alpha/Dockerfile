FROM dgraph/dgraph:latest

EXPOSE 8080

EXPOSE 9080

CMD ["dgraph", "alpha", "--my=dgraph-compose-aplha:7080", "--zero=dgraph-compose:5080", "--security", "whitelist=0.0.0.0/0"]

