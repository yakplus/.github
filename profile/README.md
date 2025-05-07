# 💊 약플 (YAK+)


<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td align="middle" valign="middle">
      <img src="https://github.com/user-attachments/assets/765fab71-04db-4e38-8c59-f7191d531b14"/>
    </td>
    <td align="middle">
      <img src="https://github.com/user-attachments/assets/53b936f1-4d42-469d-98f2-c349b1f81b17" width="45%"/>
    </td>
  </tr>
</table>

> 더 나은 약품 정보를 위한 약품 검색 플랫폼, YAK+

---

## 📖 프로젝트 소개

**💊 약플 (YAK+)**

현대인의 건강 관리에 있어 올바른 약품 선택과 정보 탐색의 중요성이 날로 높아지고 있습니다.  
하지만 기존 약품 정보 플랫폼은 방대한 데이터 속에서 핵심 정보를 직관적으로 제시하지 못해,  
사용자에게 필요한 약품을 빠르게 찾기 어렵습니다.
<br/>  

### 약플(YAK+) 은 다음과 같은 상황에서 도움을 드립니다

- 어떤 약을 골라야 할지 막막할 때
- 생각한 증상에 맞는 약품을 찾고 싶을 때
- 같은 성분을 가진 비슷한 약을 찾고싶을 때

---

## 🎯 주요 기능

<div align="center">
<img src="https://github.com/user-attachments/assets/97fbd0cc-10a0-4db0-aee2-146005861e0e" width="50%" />
</div>
<br/>

- **공공 API 기반 약품 데이터 수집 및 정제**
- **임베딩 모델 기반 벡터화 및 검색 색인 구축**
- **자연어 증상 입력 기반 약품 검색**
- **증상,성분명,약품명 입력을 통한 키워드 검색**
- **동일 성분 약품 검색 기능**

---

## 🚀 기술 스택

### Backend
<p align="left">
  <img src="https://img.shields.io/badge/Java 21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/SpringBoot 3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/MySQL 8.0.41-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA (Hibernate)-59666C?style=for-the-badge&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/JDBC-007396?style=for-the-badge&logo=java&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/SpringAI-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/SpringBatch-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />
</p>

### Frontend
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

### Deploy
<p align="left">
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>


---

## 🏛️ 아키텍처 구성
### 시스템 아키텍쳐
<div align="center">
<img src="https://github.com/user-attachments/assets/135b1b33-04f4-43ae-a114-742a2f5fe87d" width="70%" />
</div>

### 도메인 단위 헥사고날 구조
<table>
    <tr>
        <th>약품</th>
        <td align="middle"><img 
          src="https://github.com/user-attachments/assets/27883e75-f113-483f-813d-6c535ab16a33" 
          alt="Drug Diagram" 
          style="width:80%; max-width:400px; display:block; margin:0 auto;"
        /></td>
    </tr>
    <tr>
        <th>검색</th>
        <td><img 
          src="https://github.com/user-attachments/assets/6e75d77b-51c4-49e2-a0ee-e8abd39782a9" 
          alt="Search Diagram" 
          style="width:80%; max-width:400px; display:block; margin:0 auto;"
        /></td>
    </tr>
    <tr>
        <th>증상사전</th>
        <td align="middle"><img 
          src="https://github.com/user-attachments/assets/25851a90-e2d3-4a28-9109-55238788db65" 
          alt="Symptom Dictionary Diagram" 
          style="width:80%; max-width:400px; display:block; margin:0 auto;"
        /></td>
    </tr>
</table>

- Hexagonal Architecture에 기반한 모듈화 설계
- 외부 의존성(infrastructure)과 비즈니스 로직(application/domain)을 분리하여 유지보수 용이성과 기술 교체 유연성을 확보

---

## 📝 API 문서
<details>
<summary> 배치 서버 api</summary>
<img src="https://github.com/user-attachments/assets/736650c7-8933-4410-9f1b-69406ea7997e" alt="배치서버 api 구성"/>
</details>
<details>
<summary> 백엔드 서버 api</summary>
<img src="https://github.com/user-attachments/assets/fd10b42d-5ec2-44db-bd55-a6ec0fbe8ba6" alt="백엔드서버 api 구성"/>
</details>


## 👥 팀 구성

<div align="center">
<img src="https://github.com/user-attachments/assets/1f5abc39-116b-4129-a6ad-fec245f25f94" width="60%" />
<table width="80%">
  <tr>
    <td width="160px" align="center"><img src="https://github.com/chanbyoung.png" width="50px" /></td>
<td width="160px" align="center"><img src="https://github.com/HaechangLee.png" width="50px" /></td>
<td width="160px" align="center"><img src="https://github.com/LEELISE.png" width="50px" /></td>
<td width="160px" align="center"><img src="https://github.com/YJ-circle.png" width="50px" /></td>
  </tr>

  <tr>
    <td align="center"><a href="https://github.com/chanbyoung">박찬병</a>
    </td>
    <td align="center"><a href="https://github.com/HaechangLee">이해창</a>
    </td>
    <td align="center"><a href="https://github.com/LEELISE">정안식</a>
    </td>
    <td align="center"><a href="https://github.com/YJ-circle">함예정</a>
    </td>
  </tr>
</table>
</div>

