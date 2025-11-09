FROM yassern1/hadoop-spark-jupyter:1.0.3

# Maintenir l'image de base existante
# L'image de base contient déjà Hadoop, Spark, Jupyter

# Exposition des ports
EXPOSE 9870 8088 19888 9000 7077 8080 8042 4040 8081

# Définir le working directory
WORKDIR /root

# Copier les fichiers de configuration si nécessaire
# COPY config/ /opt/hadoop/etc/hadoop/

# Commande par défaut (sera override par docker-compose)
CMD ["bash", "-c", "tail -f /dev/null"]