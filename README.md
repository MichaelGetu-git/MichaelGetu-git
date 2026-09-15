## Michael Getu Muluneh

**Staff DevOps Engineer & Fullstack Lead at [Zemenay Tech](https://zemenaytech.com)** · Addis Ababa, UTC+3

Seven years shipping production software, since 2019. I write the services and I run the
infrastructure they sit on — React and React Native on the front, Python and Node behind
them, Kubernetes and AWS underneath. I can't leave anything half-owned.

📍 [michaelgetu.vercel.app](https://michaelgetu.vercel.app) · [LinkedIn](https://www.linkedin.com/in/michael-getu-063284228) · michaelgetu21@gmail.com

---

### Open source

**[galio-org/galio](https://github.com/galio-org/galio)** — contributor to the Galio React Native UI framework (3.2k ⭐). Four merged PRs:

- [#273](https://github.com/galio-org/galio/pull/273) — resolved a `GalioProvider` / React Navigation context conflict that broke apps using both
- [#272](https://github.com/galio-org/galio/pull/272) — fixed broken package exports
- [#275](https://github.com/galio-org/galio/pull/275) — navbar style optimization + provider message fix
- [#278](https://github.com/galio-org/galio/pull/278) — carried the library through the Expo SDK 54 upgrade

**[galio-test-pack](https://github.com/MichaelGetu-git/galio-test-pack)** — my own TypeScript-first rewrite of the Galio component library.

---

### Things I built because nobody asked me to

**[BGRemove](https://github.com/MichaelGetu-git/BGRemove)** — every background remover makes you upload your photo to someone's server. For an ID photo that's a privacy cost nobody prices in. This runs the segmentation model entirely in the browser via transformers.js + WebAssembly, so the image never leaves your device and there's no backend to breach.

**[multi-collab-editor](https://github.com/MichaelGetu-git/multi-collab-editor)** — real-time collaborative editing without users clobbering each other. Microservices: an API gateway fronting separate auth, document, and WebSocket collaboration services, so concurrency and access control stay independent problems.

**[Questions-jo](https://github.com/MichaelGetu-git/Questions-jo)** — an interactive leadership assessment that gives you insight as you answer rather than a score at the end. React, TypeScript, Tailwind. [Live](https://leaders-journey.vercel.app).

---

### Selected private & proprietary work

Not everything I've built is mine to publish. These are the systems I'd point at first anyway —
happy to walk through the architecture or demo any of them.

**MediScan** — clinical decision-support platform for chest X-rays. A multi-model ensemble
(YOLOv12m detection + EfficientNet-B0 classification + a Lungmask U-Net segmenter) reads 15
lung-disease classes with confidence scores and Grad-CAM heatmaps. Around the model sits a real
clinical workflow: radiologist markup, automated PDF reporting, RBAC, 2FA, AES-256 at rest,
full audit logging. FastAPI + PostgreSQL, on Kubernetes with Prometheus and Celery, covered by
pytest and Playwright suites. *Private repo.*

**EV Repair Finder** — cross-platform React Native app connecting EV drivers to certified repair
workshops across Europe, shipped on iOS and Android. Full Firebase backend (Firestore, Auth,
Cloud Functions, Messaging), Redux Toolkit, maps and navigation, multi-language i18n.
*Built at Zemenay Tech — source isn't mine to publish.*

**Leana** — real-time social features in React Native against Node.js services: live chat and
messaging over WebSockets, serving 50,000+ monthly active users. *Also Zemenay.*

---

### Stack

**Languages** TypeScript · JavaScript · Python · SQL · Dart · Bash
**Front** React · Next.js · React Native · Expo · Redux · Tailwind
**Back** Node.js · FastAPI · Express · PostgreSQL · Firebase · WebSockets
**Infra** Docker · Kubernetes (EKS) · AWS · Terraform · ArgoCD · GitHub Actions · Prometheus
**AI** PyTorch · YOLO · ONNX · transformers.js · RAG · LangChain
**Testing** Playwright · Jest · pytest

---

⚡ Manchester United, and I do my best work after midnight.
