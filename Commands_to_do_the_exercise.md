# commands to do the Exercise 

* TOKEN=$(curl http://127.0.0.1:10080/login -u user | jq -r '.token')
* curl -H "Authorization: Bearer $TOKEN" http://127.0.0.1:10080/secure

# How to generate specific key for GCP 

 * $ssh-keygen -t rsa -f gcp -C mrasmy   // gcp ==> the key name  ----- mrasmy ==> the username of the machine
