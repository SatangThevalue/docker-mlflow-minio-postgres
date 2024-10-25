<p align="center">
  <a href="" rel="noopener">
 <img width=800px height=300px src="https://media.wiki-power.com/img/20210117130925.jpg" alt="Project logo"></a>
</p>

<h3 align="center">docker-mlflow-minio-postgres</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/SatangThevalue/docker-mlflow-minio-postgres.svg)](https://github.com/SatangThevalue/docker-mlflow-minio-postgres/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/SatangThevalue/docker-mlflow-minio-postgres.svg)](https://github.com/SatangThevalue/docker-mlflow-minio-postgres/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Built Using](#built_using)

## 🧐 About <a name = "about"></a>

- postgres
- minio
- mlflow

## 🏁 Getting Started <a name = "getting_started"></a>

Docker เป็นเครื่องมือที่ช่วยให้การสร้างและจัดการแอปพลิเคชันง่ายขึ้นอย่างมาก โดยการบรรจุแอปพลิเคชันและทุกสิ่งที่ต้องการในการทำงานลงในคอนเทนเนอร์ (Container) ทำให้สามารถนำไปใช้งานได้บนเครื่องใดก็ได้ที่ติดตั้ง Docker โดยไม่ต้องกังวลเรื่องความเข้ากันได้ของระบบปฏิบัติการ
<br>
ขั้นตอนการเริ่มต้นใช้งาน Docker
<br>
ติดตั้ง Docker:
<br>
Windows และ macOS: ดาวน์โหลดและติดตั้ง Docker Desktop 
<br>ได้จาก https://www.docker.com/products/docker-desktop/
<br>
Linux: ติดตั้งตามคำแนะนำของ Docker 
<br>
สำหรับระบบปฏิบัติการของคุณ https://docs.docker.com/engine/install/

```
docker pull <image_name>: ดึง Image ลงมาจาก Docker Hub (คลัง Image สาธารณะ)
docker run <image_name>: สร้างและรัน Container จาก Image
docker ps: แสดงรายการ Container ที่กำลังทำงานอยู่
docker stop <container_id>: หยุดการทำงานของ Container
docker rm <container_id>: ลบ Container
docker images: แสดงรายการ Image ที่มีอยู่ในเครื่อง
```

## ⛏️ Built Using <a name = "built_using"></a>
- [docker](https://www.docker.com/) - docker