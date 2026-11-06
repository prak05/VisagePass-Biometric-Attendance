<div align="center">

# 👤 VisagePass Biometric Attendance
### Edge Computer Vision Attendance Verification & Audit Engine

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=F59E0B&center=true&vCenter=true&width=750&lines=VisagePass+Biometric+Attendance;Real-Time+Facial+Landmark+Recognition;128D+Euclidean+Metric+Embeddings;AWS+Rekognition+%2B+ECS+Fargate+Audit" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Rekognition_%7C_Fargate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/CV-OpenCV_%7C_Dlib_128D-0052CC?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Accuracy-99.38%25_LFW-22C55E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Preserved-Branch_Ex-gray?style=for-the-badge&logo=git" />
</p>

<img src="https://skillicons.dev/icons?i=python,aws,docker,flask,sqlite&theme=dark" alt="Stack" />

</div>

---

### 📸 Verification Telemetry

```bash
┌──(prak05@visagepass-kiosk)-[~/terminal]
└─$ python attendance_taker.py --camera 0 --anti-spoofing strict
[INFO] Optical sensor initialized: 1080p @ 60 FPS
[INFO] Face detected: Bounding box [x=240, y=180, w=320, h=320]
[INFO] 68 Facial Landmarks mapped | Eye Blink Ratio: 0.28 (Liveness Confirmed)
[INFO] Euclidean Vector Match: Prakhar Sharma (ID: EMP-0042) | Distance: 0.38 (Threshold: 0.60)
[INFO] Attendance punched: 2026-11-06T13:00:22+05:30 -> AWS DynamoDB Logged
```

---

## 🏛️ Biometric Bento Grid

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>👁️ 128D Deep Metric Vectors</h3>
      <p>Uses deep residual networks to transform facial landmarks into a 128-dimensional hypersphere vector where distance correlates directly with identity similarity.</p>
      <b>Features:</b> Invariant to glasses, pose variations, and lighting
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ Liveness & Anti-Spoofing Checks</h3>
      <p>Prevents presentation attacks using 2D photos or digital screens by monitoring dynamic micro-movements, eye-blink frequency, and 3D facial depth changes.</p>
      <b>Features:</b> Zero photo bypass • Real-time blink detection
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ AWS Rekognition & S3 Cloud Sync</h3>
      <p>Hybrid edge-to-cloud architecture: high-speed local matching with cloud verification backup and automated photo vaulting in <b>Amazon S3</b>.</p>
      <b>Features:</b> DynamoDB audit trails • CloudWatch alert logs
    </td>
    <td width="50%" valign="top">
      <h3>🏢 Multi-Tenant Attendance Dashboard</h3>
      <p>Responsive Flask & Web dashboard providing real-time roster updates, automated absenteeism detection, and exportable payroll reports.</p>
      <b>Features:</b> Automated CSV/PDF export • Role-based access
    </td>
  </tr>
</table>

---

## ⚡ Run Locally

```bash
git clone https://github.com/prak05/VisagePass-Biometric-Attendance.git
cd VisagePass-Biometric-Attendance
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

---

<div align="center">
<sub>Preserved Baseline: <a href="https://github.com/prak05/VisagePass-Biometric-Attendance/tree/Ex">branch Ex</a> • Engineered for Scalable Production Clouds</sub>
</div>
