![Objectif Libre](https://www.objectif-libre.com/wp-content/uploads/2015/04/sans-baseline-long-fblanc.png "Logo OL")

Cette image est une modification de l'image officielle Percona qui permet la mise en place d'un cluster Galera.

Son utilisation demeure identique à l'image officielle en mono docker :

```bash
$ docker run --name some-percona -e MYSQL_ROOT_PASSWORD=my-secret-pw -d objectiflibre/percona-galera:tag
```

Cette image a été conçue dans le but d'être utilisée pour bootstraper un cluster Galera dans kubernetes. Un exemple d'implementation est disponible sur [le dépôt Github suivant](https://github.com/ObjectifLibre/k8s-galera-demo/blob/master/statefulset.yaml).

# Liens rapides
  * Pour reporter un problème :
    https://github.com/ObjectifLibre/docker-percona-xtradb-cluster/issues

  * Un exemple d'utilisation :
    https://www.objectif-libre.com/fr/blog/2017/08/22/kubernetes-et-galera/
