# Big Data Labs - Hadoop & HDFS

## Lab 0 : Installation d'un Cluster Hadoop avec Docker

### Objectif du TP
- **Installer un cluster Hadoop avec Docker**
- **Se familiariser avec les commandes HDFS**

![NameNode Interface](https://github.com/DEVDLD/BigDataLabs/blob/main/images/1.png)

![Cluster Structure](https://github.com/DEVDLD/BigDataLabs/blob/main/images/2.png)

![Docker Setup](https://github.com/DEVDLD/BigDataLabs/blob/main/images/3.png)

### Interfaces Web du Cluster

**NameNode web UI**: localhost:9870  
![NameNode UI](https://github.com/DEVDLD/BigDataLabs/blob/main/images/4.png)

**Ressource Manager UI**: localhost:8088  
![ResourceManager](https://github.com/DEVDLD/BigDataLabs/blob/main/images/5.png)

**MapReduce JobHistory Server**: localhost:19888  
![JobHistory](https://github.com/DEVDLD/BigDataLabs/blob/main/images/6.png)

![HDFS Operations](https://github.com/DEVDLD/BigDataLabs/blob/main/images/7.png)

![Cluster Monitoring](https://github.com/DEVDLD/BigDataLabs/blob/main/images/8.png)

![Docker Containers](https://github.com/DEVDLD/BigDataLabs/blob/main/images/9.png)

![HDFS Commands](https://github.com/DEVDLD/BigDataLabs/blob/main/images/10.png)

![YARN Applications](https://github.com/DEVDLD/BigDataLabs/blob/main/images/11.png)

![Cluster Health](https://github.com/DEVDLD/BigDataLabs/blob/main/images/12.png)

---

## Lab 1 : Programmation avec l'API HDFS

### Objectifs du TP
- **S'initier à la programmation avec l'API HDFS**
- **Installer l'environnement de développement VScode/git/github**
- **Lire/Ecrire un fichier sur HDFS**

### I. Démarrer le Cluster Hadoop
![Cluster Startup](https://github.com/DEVDLD/BigDataLabs/blob/main/images/13.png)

### II. Programmation avec l'api HDFS

#### 1. HadoopFileStatus
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/14.png)

![HadoopFileStatus Output](https://github.com/DEVDLD/BigDataLabs/blob/main/images/15.png)

#### 2. ReadHDFS
![ReadHDFS Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/16.png)

![ReadHDFS Output](https://github.com/DEVDLD/BigDataLabs/blob/main/images/17.png)

#### 3. HDFSWrite
![HDFSWrite Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/18.png)

---

## Lab 2 :  Programmation avec l’API MapReduce

### Objectifs du TP
- **S’initier à la programmation avec L’API mapreduce**
- **Implémenter l’exemple WordCount en Java**
- **Exécuter MapReduce en Python avec Hadoop Streaming**

### I. Programmation avec l’api MapReduce en Java
- **Lancement de la commande hadoop jar /shared_volume/WordCount.jar inputfile outputfolder**
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/19.png)

![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/20.png)

- **Contenu du dossier output :**
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/21.png)

![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/22.png)

- **Contenu du fichier part-r-00000**
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/23.png)

- **Job History**
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/24.png)

![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/25.png)

### II. Programmation avec l’api MapReduce en Python avec Hadoop Streaming
- **Implémenter l’exemple wordcount à base de mapreduce en python et de l’utilitaire hadoop streaming**
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/26.png)

![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/27.png)

- **Contenu du dossier output :**
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/28.png)

- **Job History**
![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/29.png)

![HadoopFileStatus Code](https://github.com/DEVDLD/BigDataLabs/blob/main/images/30.png)