# Chaohui Zhen (甄朝晖)

Clinical medicine undergraduate @ Wenzhou Medical University · working at the
intersection of **medicine and AI engineering**.

**My research question:** *medical AI models look excellent internally and fail
quietly in the real world — how do we measure that, and what should the system
do when it doesn't know?*

My three projects form one line of work on **reliability and deployment of
medical imaging AI**:

| Project | Question it answers | Status |
|---|---|---|
| [MedKnow](https://github.com/Solren-zhen/Medknow) | When should a medical AI say "I don't know"? Uncertainty-driven referral works in-domain (referral cuts error 4.0%→0.3%) and **collapses under domain shift** — a model can be confident and wrong. | v1.0 released · [live demo](https://medknow-demo.streamlit.app) |
| [Thyroid US AI](https://github.com/Solren-zhen/thyroid-nodule-classification) | How large is the cross-dataset domain-shift gap in thyroid ultrasound AI (4 public cohorts), and do structured features (ACR TI-RADS) help? Joint training recovers ~45% of the external loss; fusion ΔAUC +0.022 (p<0.001). | manuscript in submission (STARD 2015 / TRIPOD+AI checklists) |
| Lymph-node detection (private) | YOLO-based detection of pathologically enlarged lymph nodes in laparoscopic video — real hospital data, where the bottleneck is annotation and the negative class, not architecture. | data collection |

**What I care about:** patient-level splits (no leakage), external validation,
calibration and decision curves alongside AUC, honest limitations, and
reporting guidelines (STARD / TRIPOD+AI) — the things that decide whether a
model survives contact with a real hospital.

**Toolkit:** PyTorch · EfficientNet/ResNet · YOLO · uncertainty & selective
prediction · bootstrap/paired testing · Streamlit/Gradio/HF Spaces ·
clinical rotations (internal medicine, surgery)

📫 chaohui0408.medical@outlook.com

<!--
中文一句话版（面试/简历用）：
临床医学本科生，研究方向为医学影像 AI 的可靠性评估与临床落地：
量化域漂移（甲状腺，4 公开数据集）、不确定性转诊在域漂移下的失效（MedKnow）、
真实术中数据的检测落地（淋巴结，在研）。
-->
