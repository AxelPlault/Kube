# Kube
Pour le projet Kube


Un cluster de management sur kind qui héberge Argo CD (GitOps) et Cluster API avec le provider CAPD.
Un cluster de charge prod provisionné par Cluster API, avec 3 nœuds control-plane pour la haute disponibilité.
L'application Online Boutique avec un Redis persistant (PVC).
Une pile d'observabilité : Prometheus + Grafana.
L'autoscaling à trois niveaux : HPA, VPA et Cluster Autoscaler.
La sauvegarde : Velero qui écrit vers Garage (cible S3-compatible OSS).
Un second cluster provisionné par Cluster API et synchronisé avec le même dépôt Git via un ApplicationSet Argo CD.
