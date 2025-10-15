<h1 align="center">🌸 Hello, I'm Eman</h1>
<h3 align="center">🧠 DevOps & Kubernetes Learner | 🚀 Beginner in Cloud & Containers | 💻 Passionate about Learning</h3>

---

<p align="center">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/KIND-FFCA28?style=for-the-badge&logo=kubernetes&logoColor=black"/>
  <img src="https://img.shields.io/badge/YAML-000000?style=for-the-badge&logo=yaml&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

---

## 🌈 About This Project  

> 🎯 My **first Kubernetes project** — created after learning Kubernetes for just a few days!  
> It covers everything from **Pods ➜ Deployments ➜ Services ➜ User Access**, all deployed on a **KIND Cluster** locally.

---

## 🧩 What I Learned  

| Topic | Description |
|-------|-------------|
| 📦 **Pods** | The smallest deployable unit in Kubernetes |
| 🌀 **ReplicaSets** | Ensure desired number of pods are always running |
| ⚙️ **Deployments** | Manage, update, and roll out app versions easily |
| 🧱 **Namespaces** | Logical separation for organizing resources |
| 🔁 **Rolling Updates** | Deploy new versions without downtime |
| 💾 **PV & PVC** | Persistent storage management |
| 🌐 **Services** | Expose apps to users |
| ☁️ **KIND / Minikube** | Local Kubernetes cluster environments |

---

## 🛠️ My Cluster Setup  

```bash
NAME                        STATUS   ROLES           AGE    VERSION
tws-cluster-control-plane   Ready    control-plane   7d3h   v1.31.2
tws-cluster-worker          Ready    <none>          7d3h   v1.31.2
tws-cluster-worker2         Ready    <none>          7d3h   v1.31.2
tws-cluster-worker3         Ready    <none>          7d3h   v1.31.2

---

🚀 Step-by-Step Kubernetes Deployment
🪣 Step 1 — Create Namespace
kubectl create namespace demo-web

🧩 Step 2 — Deploy Pod
kubectl apply -f pod.yml -n demo-web

⚙️ Step 3 — Create Deployment
kubectl apply -f deployment.yml -n demo-web

🌐 Step 4 — Expose as a Service
kubectl apply -f service.yml -n demo-web

🔍 Step 5 — Verify
kubectl get all -n demo-web

🌍 Access the Web App
Since you’re using KIND, open in your browser:
👉 http://localhost:30080
If it doesn’t open on that port, use port-forwarding:
.kubectl port-forward svc/web-service -n demo-web 8080:80
Then visit 👉 http://localhost:8080

---

💡 My Tech Stack
<p align="center"> <img src="https://skillicons.dev/icons?i=kubernetes,docker,linux,bash,git,vscode" /> </p>
📊 Project Progress
Metric	Status
🌟 Cluster Created	✅
🧱 Pods Deployed	✅
⚙️ Deployments Working	✅
🌐 Service Accessible	✅
💻 Project Completed	🏁

---

📘 Summary
✔ Learned how Kubernetes works internally
✔ Built a local KIND cluster
✔ Created Pods, Deployments, and Services
✔ Exposed the app to local browser successfully

