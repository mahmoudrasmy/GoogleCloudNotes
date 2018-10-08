# Important Commands for Gcloud Console

* To list all Zones in specific region ==> $gcloud compute zones list | grep us-central1
* To set a specific Zone to use ==> $gcloud config set compute/zone europe-west1-d
* To create a Virtual machine ==> $gcloud compute instances create ubuntu --image-project ubuntu-os-cloud --image ubuntu-1604-xenial-v20160420c
* $gcloud compute --project "atomic-order-195510" ssh --zone "europe-west4-b" "instance-1"
