---
marp: true
title: Seven Deadly Sins of Container Security
theme: uncover
paginate: true
_paginate: false
---
![bg contain](https://s3-us-west-2.amazonaws.com/appsecng-images/logo.png)

---
# <!--fit--> Seven Deadly Sins

of Container Security

---
# Remember

* These sins can make their way to orchestration systems like Kubernetes, Mesos, ECS, etc
* Depending on Vulnerabilities in the apps held by these containers, the attack could be worse/not
* Lot of these sins are the "best" way to run containers for many apps. And thats bad

---
# <!--fit--> 1. Running as uid=0
---
# <!--fit--> 2. Exposing the Docker Socket to a Container
---
# <!--fit--> 3. Running with `--privileged`
---
# <!--fit--> 4. Secrets in Container
---
# <!--fit--> 5. Running "Bloated" Containers
---
# <!--fit--> 6. Running `--net=host`
---
# <!--fit--> 7. Running > 1 service / container
---
![bg contain right](https://s3-us-west-2.amazonaws.com/appsecng-images/logo.png)
* Follow [@abhaybhargav](https://www.twitter.com/abhaybhargav) on Twitter
* Subscribe to this channel for more videos
* [abhaybhargav.com](https://www.abhaybhargav.com)
