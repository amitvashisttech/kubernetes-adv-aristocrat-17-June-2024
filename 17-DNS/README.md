```
306  kubectl apply -f 01-busybox.yaml
  307  kubectl  get pods
  308  kubectl  get svc
  309  kubectl  exec -it busybox -- cat /etc/resolv.conf
  310  kubectl  get svc -n kube-system
  311  kubectl  describe svc kube-dns -n kube-system
  312  kubectl  get pods -A -o wide
  313  kubectl  exec -it busybox -- cat /etc/resolv.conf
  314  kubectl  exec -it busybox -- nslookup kubernetes
  315  kubectl  exec -it busybox -- nslookup python-webapp-svc
  319  kubectl  exec -it busybox -- wget nginx
  320  kubectl  exec -it busybox -- sh
  321  kubectl  exec -it busybox -- /etc/resolv.conf
  322  kubectl  exec -it busybox -- cat /etc/resolv.conf
  ```
