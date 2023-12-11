# 🚑 Third-01 Project : 대구 교통사고 피해 예측 AI 경진대회


## Abstract
> 각 교통사고에서 발생하는 사망, 경상, 중상, 부상 인원 수로 만들어진 ECLO 지수 예측

<h2> 👪 Team </h2>

> Name : 데마시아

<h3> 👪 Members </h3>
<table>
  <tr>
    <td> <div align=center> 👑 </div> </td>
    <td> <div align=center>  1 </div> </td>
    <td> <div align=center>  2 </div> </td>
    <td> <div align=center>  3 </div> </td>
  </tr>
  <tr>
    <td> <div align=center> <b>김도연</b> </div> </td>
    <td> <div align=center> <b>서상혁</b> </div> </td>
    <td> <div align=center> <b>김다운</b> </div> </td>
    <td> <div align=center> <b>신동혁</b> </div> </td>
  </tr>
  <tr>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/8d57d084-1d8c-4306-8765-b8d05cd1fc73" width="200" height="300"/> </td>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/a7be969c-b5ad-4f14-9dd9-cb72640c49a3" width="200" height="300"/> </td>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/37f278cf-3c62-44ca-a49d-6a7799078b4c" width="200" height="300"/> </td>
    <td> <img alt="Github" src ="https://github.com/Daw-ny/Upstage_02nd_Proj/assets/76687996/cbd0651a-4d70-41d8-aad3-b654c42f16e2" width="200" height="300"/> </td>
  </tr>
  <tr>
    <td> <div align=center> <a href="https://github.com/d-yeon"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
    <td> <div align=center> <a href="https://github.com/S-RSH"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
    <td> <div align=center> <a href="https://github.com/Daw-ny"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
    <td> <div align=center> <a href="https://github.com/HyeokHam"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </td>
  </div> </tr>
</table>

<h3> 🛑 Role & Rule </h3>

> ### Ground Rule
> - 회의를 통해 각자의 역할을 정하고 다음 회의까지 진행된 상황을 공유하여 서로의 피드백을 듣고 필요한 부분은 수정하였다.
> - 제출 기회가 제한되어 있기 때문에 제출할 때 꼭 이야기 할것
> - 노션에 자신이 올렸던 코드의 기록에 대해 작성할 것
> - 휴식시에는 꼭 다같이 쉴것


<table>
  <tr>
    <td> <div align=center> <b> 이름 </b> </div> </td>
    <td> <div align=center> <b> 역할 </b> </div> </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 김도연 </b> </div> </td>
    <td> <b>EDA </b>(데이터 칼럼 간 관계 확인, 빅데이터 마트 데이터 확인 및 전처리, 특이케이스 처리)</br> 
         <b>파생변수 </b>(대구 빅데이터 마트 데이터 Count) </br> 
         <b>진행상황 정리 </b>(진행 방향 문서화, 회의 내용 기록)</br>
         <b>모델링 </b>(AutoML 모델링, 부상자수 예측 모델 구현) </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 서상혁 </b> </div> </td>
    <td> <b>EDA </b>(데이터 칼럼 간 관계 확인, 빅데이터 마트 데이터 확인 및 전처리)</br> 
         <b>파생변수 </b>(대구 빅데이터 마트 데이터 Count, OneHotEncoding, Split 등을 활용한 범주형 변수 처리, Season과 같은 특성 변수 생성) </br> 
         <b>진행상황 정리 </b>(진행 방향 문서화, 코드 병합 및 정리)</br>
         <b>모델링 </b>(AutoML 모델링, 중상자수 예측 모델 구현) </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 김다운 </b> </div> </td>
    <td> <b>EDA </b>(데이터 칼럼 간 관계 확인, 빅데이터 마트 데이터 확인 및 전처리, 특이케이스 처리)</br> 
         <b>파생변수 </b>(대구 빅데이터 마트 데이터 Count, 반응변수 log화, 제공해준 변수 Count) </br> 
         <b>진행상황 정리 </b>(진행 방향 문서화, 회의 내용 기록, 모델링 및 제출 결과 기록)</br>
         <b>모델링 </b>(AutoML 모델링, 사망자수 예측 모델 구현) </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 신동혁 </b> </div> </td>
    <td> <b>EDA </b>(데이터 칼럼 간 관계 확인, Country wide Data EDA)</br> 
         <b>파생변수 </b>(OneHotEncoding, Split 등을 활용한 범주형 변수 처리, Season과 같은 특성 변수 생성) </br> 
         <b>진행상황 정리 </b>(진행 방향 문서화, 회의 내용 기록)</br>
         <b>모델링 </b>(AutoML 모델링, 경상자수 예측 모델 구현) </td>
  </tr>
</table>

<h3> 📽️ Project Intro </h3>

<table>
  <tr>
    <td> <div align=center> <b> Subject </b> </div> </td>
    <td> 대구에서 발생한 교통사고 데이터를 활용하여 앞으로의 교통사고의 피해에 대해 예측할 수 있는 모델 구현 </td>
  </tr>
  <tr>
    <td> <div align=center> <b> Processing </b> </div> </td>
    <td> 1. 데이터의 각 칼럼이 어떤 의미를 갖는지 확인하고 각 칼럼의 분포 및 결측, 이상치 존재여부 확인 </br>
         2. 데이터 맞춤 전처리 및 이상치 대치 이후 기초통계량을 확인하고 병의 진행 집단별로 분석 가설을 세우고 적합한 방법으로 검증 </br>
         3. Machine Learning Modeling을 통한 최적의 모델 생성하기
  </td>
  </tr>
  <tr>
    <td> <div align=center> <b> Develop Enviroment </b> </div> </td>
    <td> <tt>Tool</tt>: Jupyter Notebook, VS Code, Microsoft Excel</td>
  </tr>
  <tr>
    <td> <div align=center> <b> Communication Enviroment </b> </div> </td>
    <td> <tt>Notion</tt>: 프로젝트를 위한 역할분담, 아이디어 브레인 스토밍, 프로젝트 관련 회의 내용 기록 </br> 
         <tt>SLACK, Zoom, Discord</tt>: 실시간 비대면 회의 </td>
  </tr>
</table>

<h3> 📆 Project Procedure </h3>

>  자세한 진행 내용은 [대구 교통사고 예측](https://www.notion.so/AI-c39da23006f84545be702ac1192e5241?pvs=4)에서 확인하실 수 있습니다.

<h3> 📂 Project Structure </h3>

> - TA
>> - Code
>>> - 각종 EDA와 전처리 그리고 Modeling을 적용한 코드가 담겨있습니다.
>>>
>> - Data
>>> - 데이콘에서 제공해준 데이터 및 전처리 이후 활용했던 데이터가 담겨 있습니다.
>>>
>> - Model
>>> - AutoML을 활용하여 적용한 모델 중 가장 성능이 좋은 모델에 대해 결과물이 상세히 담겨 있습니다.

<h3> ⚙️ Architecture </h3>
<table>
  <tr>
    <td> <div align=center> <b> 분류 </b> </div> </td>
    <td> <div align=center> <b> 내용 </b> </div> </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 모델 </b> </div> </td>
    <td> <tt>RandomForest</tt>, <tt>XGBoost</tt>, <tt>LightGBM</tt>, <tt>CatBoost</tt>, <tt>AutoML</tt> </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 데이터 </b> </div> </td>
    <td> <tt>Data</tt> 데이콘에서 제공해준 데이터: 폴더 안에서 확인하실 수 있습니다. </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 모델 평가 </b> </div> </td>
    <td> RMSE를 산출하여 비교 후 가장 낮은 값을 가진 모델을 선택 </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 모델 적용 방법 </b> </div> </td>
    <td> 각 모델을 활용하여 최종 public score을 계산하고 rmse값이 낮은 모델을 선정하여 Ensemble 또는 stacking하는 방법 적용 </td>
  </tr>
</table>
