FROM dgraph/dgraph:latest

EXPOSE 8080

EXPOSE 9080

CMD ["dgraph", "alpha", "--my=dgraph-compose-aplha.railway.internal:7080", "--zero=dgraph-compose.railway.internal:5080", "--security", "whitelist=0.0.0.0/0"]

