FROM dgraph/dgraph:latest

EXPOSE 8080

EXPOSE 9080

CMD ["dgraph", "alpha", "--my=aplha.railway.internal:7080", "--zero=zero.railway.internal:5080", "--security", "whitelist=0.0.0.0/0"]

