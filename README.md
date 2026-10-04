# Build and Deploy a Simple Guestbook Application

Final Project for IBM Course: **Introduction to Containers w/ Docker, Kubernetes & OpenShift**

## Project Overview
In this final project, we build and deploy a simple guestbook application consisting of a web front end where users can enter text and submit it. For all of these, Kubernetes Deployments and Pods are created, Horizontal Pod Autoscaling (HPA) is applied to dynamically scale based on CPU utilization, and rolling updates and rollbacks are performed.

---

## Final Project Deliverables & Submission Links

| Task # | Task Description | Submission File / Link | Points |
| :---: | :--- | :--- | :---: |
| **Task 1** | Updated Dockerfile showing all details, including COPY commands and the EXPOSE instruction | [Task 1: Dockerfile](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task1_dockerfile.txt) / [v1/guestbook/Dockerfile](https://github.com/sohamd530-eng/guestbook/blob/main/v1/guestbook/Dockerfile) | **1 Point** |
| **Task 2** | Terminal output showing image pushed to IBM Cloud Container Registry with tag v1, using 'ibmcloud cr images' | [Task 2: ibmcloud cr images](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task2_ibmcloud_cr_images.txt) | **1 Point** |
| **Task 3** | Code from index.html showing default <title> and <h1> | [Task 3: Default index.html](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task3_index_html_v1.html) | **1 Point** |
| **Task 4** | Terminal output showing Horizontal Pod Autoscaler (HPA) created with 0 replicas | [Task 4: HPA 0 Replicas](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task4_hpa_0_replicas.txt) | **1 Point** |
| **Task 5** | Terminal output showing increased replicas, confirming autoscaling is working | [Task 5: Autoscaling Working](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task5_hpa_increased_replicas.txt) | **2 Points** |
| **Task 6** | Terminal output showing Docker push of updated image, including final digest line | [Task 6: Docker Push Digest](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task6_docker_push_digest.txt) | **2 Points** |
| **Task 7** | Terminal output confirming updated deployment using 'kubectl apply -f deployment.yml' | [Task 7: Deployment Configured](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task7_deployment_configured.txt) | **1 Point** |
| **Task 8** | Updated code from index.html showing <title> and <h1> as "Guestbook â€“ v2" | [Task 8: index.html v2](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task8_index_html_v2.html) | **2 Points** |
| **Task 9** | Terminal output showing deployment rollout history with CPU-related changes | [Task 9: Rollout History CPU](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task9_rollout_history_cpu.txt) | **2 Points** |
| **Task 10** | Terminal output from 'kubectl get rs' showing ReplicaSets after rollback | [Task 10: ReplicaSets Rollback](https://github.com/sohamd530-eng/guestbook/blob/main/tasks/task10_kubectl_get_rs_rollback.txt) | **2 Points** |
| **Total** | | | **15 Points (100%)** |