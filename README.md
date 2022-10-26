

## 1. 소개🎯

**주제**
  
- 빅데이터 분석 및 데이터 파이프라인 프레임워크 구축
 
**문제 정의**

- 금융, 유통군들에서 빅데이터는 필수불가결한 솔루션
- 빅데이터 구축 시 마다 분석/설계/인력 등 많은 견적이 요소가 포함되어 금액 부담이 발생   
 
**목표**

- MLOps 구축하여 파이프라이닝되는 과정까지를 표준화
- 공통된 Middleware 프레임워크를 구축하기 위한 핵심 요소를 구현

<br>

## 2. S/W architecture🖼

![image](https://user-images.githubusercontent.com/76522430/198015775-2f8a6f8b-e599-443a-adb0-253748109819.png)

<br>


**Environment**
   <table>
     <tr>
       <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png" width="70" height="70"></td>
       <td><img src="https://raw.githubusercontent.com/jsx-ir/logo/master/jsx.png" width="70" height="70"></td>
       <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/768px-Python-logo-notext.svg.png" width="70" height="70"></td>
       <td><img src="https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FBHr9w%2Fbtq7tsvu04R%2FdmBJ3ANlWgUxKZDM6yxXy0%2Fimg.png" width="95" height="70"></td>
       <td><img src="https://media.vlpt.us/images/sgh002400/post/005be64e-a3e4-4535-9b97-72876a30ef97/MySQL.png" width="90" height="70"></td>
       <td><img src="https://prev.github.io/attachs/full-stack-flask/logos/sqlalchemy.png" width="70" height="18"></td>
       <td><img src="https://media.vlpt.us/images/june0313/post/a2bbe956-5158-41d0-85f4-732de86c81b4/3630px-Nginx_logo.png" width="105" height="70"></td>
     </tr>
     <tr>
       <td align=center>Javascript</td>
       <td align=center>JSX</td>
       <td align=center>Python<br>3.8 </td>
       <td align=center>Flask</td>
       <td align=center>mySQL</td>
       <td align=center>SQL<br>Alchemy</td>
       <td align=center>Ngnix</td>
     </tr>
   </table>


   > ![ubuntu](https://img.shields.io/badge/ubuntu-20.04-orange), ![MySQL](https://img.shields.io/badge/-MySQL-%2300618a)
    <br>

<br><br>
**Library**
   <table>
     <tr>
       <td><img src="https://pytorch.org/assets/images/pytorch-logo.png" width="80" height="80"></td>
       <td><img src="https://media.vlpt.us/images/chez_bono/post/487c1fc1-4d58-4a97-aaaf-e0d1d91c0cb6/React.js_logo-512.png" width="70" height="70"></td>
       <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Axios_logo_%282017%29.svg/1280px-Axios_logo_%282017%29.svg.png" width="70" height="20"></td>
       <td><img src="https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbIIBwO%2Fbtrc2Lw7HBs%2FP4hJVVvKkEGfDu9XRzkiq1%2Fimg.png" width="50" height="50"></td>  
     </tr>
     <tr>
   ​    <td align=center>Pytorch</td>
   ​    <td align=center>React</td>
   ​    <td align=center>Axios</td>
   ​    <td align=center>Recoil</td>
     </tr>
   </table>

   > ![](https://img.shields.io/badge/-tqdm-green), ![pandas](https://img.shields.io/badge/pandas-25b72d),
   > ![numpy](https://img.shields.io/badge/numpy-209d8d), ![mxnet](https://img.shields.io/badge/-mxnet-%230393d6), ![gluonNLP](https://img.shields.io/badge/-GluonNLP-%23d7ebfe), ![](https://img.shields.io/badge/-sentencepiece-%239fa1a4), ![](https://img.shields.io/badge/-Counter-black), ![](https://img.shields.io/badge/-Slate-%23741e4b), ![](https://img.shields.io/badge/-PyMySQL-blueviolet), ![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-%23cb1700),

   <details>
       <summary style="color: gray;">Details</summary>


       alembic==1.7.5
       certifi==2019.11.28
       chardet==3.0.4
       click==8.0.3
       Cython==0.29.25
       dbus-python==1.2.16
       distro-info===0.23ubuntu1
       filelock==3.4.0
       Flask==2.0.2
       Flask-Cors==3.0.10
       Flask-Migrate==3.1.0
       Flask-SQLAlchemy==2.5.1
       flatbuffers==2.0
       gluonnlp==0.10.0
       graphviz==0.8.4
       greenlet==1.1.2
       huggingface-hub==0.2.1
       idna==2.8
       importlib-metadata==4.8.2
       importlib-resources==5.4.0
       itsdangerous==2.0.1
       Jinja2==3.0.3
       joblib==1.1.0
       kobert @ git+https://github.com/SKTBrain/KoBERT.git@77466ab67f2700f7aad3ae59c31b888eebd9e509
       Mako==1.1.6
       MarkupSafe==2.0.1
       mxnet==1.8.0.post0
       numpy==1.21.4
       onnxruntime==1.10.0
       packaging==21.3
       pandas==1.3.4
       protobuf==3.19.1
       PyGObject==3.36.0
       PyMySQL==1.0.2
       pyparsing==3.0.6
       python-apt==2.0.0+ubuntu0.20.4.6
       python-dateutil==2.8.2
       pytz==2021.3
       PyYAML==6.0
       regex==2021.11.10
       requests==2.22.0
       requests-unixsocket==0.2.0
       sacremoses==0.0.46
       sentencepiece==0.1.96
       six==1.14.0
       SQLAlchemy==1.4.28
       tokenizers==0.8.1rc1
       torch==1.10.0
       tqdm==4.62.3
       transformers==3.0.2
       typing_extensions==4.0.1
       unattended-upgrades==0.1
       urllib3==1.25.8
       Werkzeug==2.0.2
       zipp==3.6.0

   </details>

   <br>

**Skills**

   <table>
     <tr>
       <td><img src="https://img2.quasarzone.com/editor/2021/07/02/f6381015430ce5a4e608b3865a1a96a0.png" width="55" height="55"></td>
       <td><img src="https://blog.kakaocdn.net/dn/ICVj3/btqw8CnwRqm/UD96COJ6GKk4Y9aF4w46gK/img.png" width="80" height="77"></td>
     </tr>
     <tr>
       <td align=center>KoBERT<br>2.0</td>
       <td align=center>NVIDIA<br>CUDA</td>
     </tr>
   </table>

   > ![colab](https://img.shields.io/badge/google-colab-orange), ![](https://img.shields.io/badge/-transformers-brightgreen)

### 4. 데이터
  
1. Used DataSets
   - [뉴욕택시데이터셋](https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/data)<br>

   <br>

### 5. 팀원 역할

| Name   | Position   |
| ------ | ---------- |
| 박정기 | MLflow, Airflow, Pyspark (Reader) |
| 권순빈 | Hive, Datawarehouse         | 
| 정인식 | Hadoop eco system | 
| 최순재 | Pyspark, ETL, Visualization  |



**본인이 기여한 부분**
 

<br>

<br> <br>
