# GCP-Certificate-Manager_confgiure_with_ingress
configure the GKE ingress with a preshared cert https://cloud.google.com/kubernetes-engine/docs/how-to/load-balance-ingress#summary_of_external_ingress_annotations

# First We need to Create a Classic certificates on GCP Console and upload your .crt and .key file of self-managed SSL certificates.

# Second we need to mention the certificates name into Ingress annotations "ingress.gcp.kubernetes.io/pre-shared-cert" to use the GCP-Certificate-Manager for your ssl on GKE.


