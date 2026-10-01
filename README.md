<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,100:38B2AC&height=220&section=header&text=Bhargava%20Chary%20Basangari&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Engineering%20%E2%80%A2%20AI%20Infrastructure%20%E2%80%A2%20Adaptive%20Learning&descAlignY=58&descSize=18"
    alt="Bhargava Chary Basangari"
  />
</div>

<h3 align="center">
  Backend Developer &nbsp;|&nbsp; 3+ years building platforms used by 1,000+ students
</h3>

<p align="center">
  I build and operate secure backend platforms, AI-assisted assessment systems, and shared GPU infrastructure used in real academic and research environments.
</p>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=20&pause=1000&color=38B2AC&center=true&vCenter=true&width=600&lines=Building+Secure+Backend+APIs;Designing+AI-Driven+Assessment+Platforms;Managing+Distributed+GPU+Clusters;Writing+about+NestJS+%26+Backend+Dev" alt="Typing SVG" />
  </a>
</div>

<p align="center">
  <a href="https://linkedin.com/in/bhargavacharyb">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/bhargavachary123">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://medium.com/@bhargavacharyb">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium">
  </a>
  <a href="https://orcid.org/0009-0004-6057-6228">
    <img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID">
  </a>
</p>

---

## Impact, in Numbers

<table>
  <tr>
    <td align="center" width="25%"><h2>40%</h2>reduction in manual grading time through GPT-4 + async queues</td>
    <td align="center" width="25%"><h2>30+</h2>production REST APIs designed and maintained</td>
    <td align="center" width="25%"><h2>500+</h2>students supported in distributed programming labs</td>
    <td align="center" width="25%"><h2>3,000+</h2>students served across academic platforms</td>
  </tr>
</table>

---

## Selected Production Systems

Production and internal platforms I have helped engineer, deploy, and operate:

<table>
<tr>
  <td width="30%">
    <strong>GPU Research Lab</strong><br>
    <sub>GPU Scheduling & Research Infrastructure</sub>
  </td>
  <td width="70%">
    Engineered and operated a shared GPU research environment serving <strong>100+ students and researchers</strong> on <strong>NVIDIA A100 and H200</strong> servers. Extended <strong>JupyterHub</strong> with custom GPU governance covering <strong>role-based booking, mediator approvals, conflict-safe scheduling, time-bound access, slot release, and expiry enforcement</strong>. Used <strong>DockerSpawner</strong> and the NVIDIA Container Toolkit to isolate workloads and automate GPU lifecycle management.
    <br>
    <img src="https://img.shields.io/badge/Status-Live%20%E2%80%94%20Internal%20Network-38B2AC?style=flat-square&logo=jupyter&logoColor=white">
    <br>
    <sub>Production GPU infrastructure supporting academic research. Deployment details are private for security reasons.</sub>
  </td>
</tr>
  <tr>
  <td width="30%">
    <strong>Distributed Auto-Grading Platform</strong><br>
    <sub>JupyterHub + nbgrader Infrastructure</sub>
  </td>
  <td width="70%">
    Built a distributed learning and assessment platform used by <strong>500+ students</strong> for programming labs and assignments. Designed a scalable <strong>JupyterHub + nbgrader</strong> environment with automated deployment and configuration management through <strong>Ansible</strong>, ensuring consistent setups across multiple Linux servers. Implemented role-based workflows for <strong>administrators, instructors, graders, teachers, and students</strong>, covering course management, assignment distribution, automated grading, manual review, and centralized grade publishing.
    <br>
    <img src="https://img.shields.io/badge/Status-Live%20%E2%80%94%20Internal%20Network-38B2AC?style=flat-square&logo=jupyter&logoColor=white">
  </td>
</tr>
 <tr>
  <td width="30%">
    <strong>DrugParadigm</strong><br>
    <sub>AI-Powered Computational Biology Platform</sub>
  </td>
  <td width="70%">
    Engineered backend services for a computational biology platform using <strong>NestJS</strong>, <strong>TypeORM</strong>, <strong>MySQL</strong>, and <strong>Redis</strong>. Implemented secure authentication with <strong>SuperTokens</strong>, asynchronous job processing using <strong>BullMQ</strong>, REST APIs, rate limiting, logging, and Docker-based deployment.
    <br>
    <a href="https://drugparadigm.com/">
      <img src="https://img.shields.io/badge/Live-drugparadigm.com-38B2AC?style=flat-square&logo=googlechrome&logoColor=white">
    </a>
  </td>
</tr>
  </tr>
  <tr>
    <td width="30%"><strong>Prashmanch</strong><br><sub>AI Assessment & Evaluation Platform</sub></td>
    <td width="70%">
      Built NestJS + TypeORM backend services integrating <strong>OpenAI GPT-4</strong> through <strong>BullMQ</strong> asynchronous queues, reducing manual grading time by <strong>40%</strong> and processing <strong>1,000+ assessment submissions</strong> through reliable background workflows.<br>
      <a href="https://prashnamanch.tesseractonline.com/"><img src="https://img.shields.io/badge/Live-prashnamanch.tesseractonline.com-38B2AC?style=flat-square&logo=googlechrome&logoColor=white"></a>
    </td>
  </tr>
  <tr>
  <td width="30%">
    <strong>Project School</strong><br>
    <sub>Academic Project Management Platform</sub>
  </td>
  <td width="70%">
    Built and maintained <strong>30+ production REST APIs</strong> using <strong>NestJS</strong> and <strong>TypeORM</strong> for project enrollment, group formation, mentor allocation, project tracking, evaluations, and related academic workflows serving <strong>1,000+ students</strong>. Implemented <strong>JWT + RBAC</strong> to enforce least-privilege access and optimized high-traffic database queries to reduce response latency. Designed <strong>concurrency-safe enrollment workflows</strong> that prevent duplicate enrollments, duplicate group creation, race conditions, and inconsistent transactional states.<br>
    <a href="https://ps.kmitonline.com/">
      <img src="https://img.shields.io/badge/Live-ps.kmitonline.com-38B2AC?style=flat-square&logo=googlechrome&logoColor=white">
    </a>
  </td>
</table>

---

## Independent Projects

Independent products where I owned architecture, implementation review, deployment, and ongoing improvements:

<table>
<tr>
  <td width="30%">
    <strong>VR Associates</strong><br>
    <sub>Tax & GST Consulting Platform</sub>
  </td>
  <td width="70%">
    Developed and deployed a responsive business website using <strong>React</strong>, <strong>Vite</strong>, and <strong>Tailwind CSS</strong>. Built service pages, blogs, event management, and enquiry workflows with <strong>SEO optimization</strong> using React Helmet Async. Deployed on <strong>Cloudflare Pages</strong>, delivering a fast, scalable, and search-engine-friendly platform for a professional tax and GST consulting firm.
    <br>
    <a href="https://vrassociatestax.com/">
      <img src="https://img.shields.io/badge/Live-vrassociatestax.com-38B2AC?style=flat-square&logo=googlechrome&logoColor=white">
    </a>
  </td>
<tr>
  <td width="30%">
    <strong>Jai Ganesha Bhakthi Samithi</strong><br>
    <sub>Community & Environmental Platform</sub>
  </td>
  <td width="70%">
    Built and deployed a web platform using <strong>Next.js</strong> and <strong>TypeScript</strong>. Developed dynamic event galleries with the <strong>Google Drive API</strong>, automated email notifications with <strong>Nodemailer</strong>, added schema-based form validation using <strong>Zod</strong>, and deployed the application on <strong>Vercel</strong>.
    <br>
    <a href="https://jaiganeshabakthisamithi.org/">
      <img src="https://img.shields.io/badge/Live-jaiganeshabakthisamithi.org-38B2AC?style=flat-square&logo=googlechrome&logoColor=white">
    </a>
  </td>
</tr>
</table>

---

## Open Source

<table>
  <tr>
    <td width="34%">
      <a href="https://github.com/bhargavachary123/zero-to-nestjs"><strong>Zero-to-NestJS</strong></a><br>
      Modular NestJS reference backend covering JWT authentication, RBAC, TypeORM, Redis caching, background queues, scheduling, file uploads, rate limiting, and structured logging.
    </td>
    <td width="33%">
      <a href="https://github.com/bhargavachary123/Gpu-Benchmark-Suite"><strong>Gpu-Benchmark-Suite</strong></a><br>
      Professional Python and CUDA benchmarking suite for comparing NVIDIA GPUs across compute, training, inference, power efficiency, thermal behavior, and NVML telemetry.
    </td>
    <td width="33%">
      <a href="https://github.com/bhargavachary123/Nestjs-boilerplate"><strong>Nestjs-boilerplate</strong></a><br>
      NestJS starter with JWT authentication, role-based authorization, MySQL and TypeORM integration, Redis caching, logging, Swagger documentation, file uploads, and Docker support.
    </td>
  </tr>
</table>

---

## About Me

I'm an **Associate Software Engineer at Teleparadigm Networks Ltd.** with 2+ years of experience building secure APIs, backend automation, AI-assisted assessment platforms, and multi-user GPU infrastructure for academic and research environments.

**Day to day:**

* Design backend services with **NestJS, FastAPI, Flask, TypeORM, and MySQL**
* Integrate GPT APIs into production workflows using async queue processing (BullMQ)
* Implement JWT/RBAC authentication, rate limiting, logging, and Swagger-documented APIs
* Operate GPU infrastructure — **multi-user NVIDIA A100 and H200** — via JupyterHub, DockerSpawner, and NVIDIA Container Toolkit
* Support Linux/Docker infrastructure for containerized, multi-user environments
* Mentor developers and interns on backend engineering and AI systems
* Publish technical tutorials on backend architecture and secure API design

---

## Education

<table>
  <tr>
    <td width="70%"><strong>B.Tech, Computer Science</strong><br>Keshav Memorial Institute of Technology, Hyderabad</td>
    <td width="30%">2021 – 2024<br>CGPA 7.9/10</td>
  </tr>
  <tr>
    <td><strong>Diploma, Computer Science</strong><br>Government Institute of Technology, Secunderabad</td>
    <td>2017 – 2020<br>CGPA 8.6/10</td>
  </tr>
</table>

---

## Tech Stack

**Backend & APIs**
<br>
<img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,express,py,fastapi,flask&perline=8" alt="Backend technologies">

**AI, GPU & Data**
<br>
<img src="https://skillicons.dev/icons?i=mysql,mongodb&perline=8" alt="AI and database technologies">
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/NVML-76B900?style=flat-square&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/JupyterHub-F37626?style=flat-square&logo=jupyter&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI_GPT--4-412991?style=flat-square&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/BullMQ-DD0031?style=flat-square&logo=redis&logoColor=white">

**Frontend**
<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,vite,redux,html,css&perline=8" alt="Frontend technologies">

**Infrastructure & Security**
<br>
<img src="https://skillicons.dev/icons?i=docker,linux,git,github&perline=8" alt="Infrastructure technologies">

---
## Research & Technical Mentorship

- Mentored multiple research groups working on **DL-based siRNA–mRNA efficacy prediction**.

---

## Technical Writing

I publish practical tutorials on Medium covering NestJS architecture, RBAC, JWT authentication, TypeORM integration, and secure API design.

<p>
  <a href="https://medium.com/@bhargavacharyb">
    <img src="https://img.shields.io/badge/Read_my_articles_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Read articles on Medium">
  </a>
</p>

---

## Let's Connect

Open to collaborating on backend and platform engineering, AI-assisted education tools, GPU infrastructure automation, and applied security systems.

<p align="center">
  <a href="https://linkedin.com/in/bhargavacharyb">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn">
  </a>
  <a href="https://medium.com/@bhargavacharyb">
    <img src="https://img.shields.io/badge/Follow_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Follow on Medium">
  </a>
    <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:38B2AC,100:0F766E&height=120&section=footer"
    alt="Footer"
  />
</div>

