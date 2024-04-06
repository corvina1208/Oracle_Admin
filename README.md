
<img src="https://github.com/corvina1208/Oracle_Admin/assets/157337929/715f35d6-0331-4da1-851a-b91bf6b0508d.png">  
<br/>
<br/>

**실습 환경 : ORACLE 11g, 19c**  

<br/>

# Oracle Admin

### 1. 오라클 구조
- 1-1. 오라클 데이터베이스 서버 구조 : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-1.%20%EC%98%A4%EB%9D%BC%ED%81%B4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4%20%EC%84%9C%EB%B2%84%20%EA%B5%AC%EC%A1%B0.md)
- 1-2. 오라클 데이터베이스 메모리 구조 : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-2.%20%EC%98%A4%EB%9D%BC%ED%81%B4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4%20%EB%A9%94%EB%AA%A8%EB%A6%AC%20%EA%B5%AC%EC%A1%B0.md)
- 1-3. Shared Pool : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-3.%20Shared%20Pool.md)
- 1-4. Database Buffer Cache : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-4.%20Database%20Buffer%20Cache.md)
- 1-5. Redo Log Buffer : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-5.%20Redo%20Log%20Buffer.md)
- 1-6. Large Pool : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-6.%20Large%20Pool.md)
- 1-7. Java Pool / Stream Pool : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-7.%20Java%20Pool%2C%20Stream%20Pool.md)
- 1-8. PGA(Program Global Area) : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-8.%20PGA.md)
- 1-9. DBWn(DB Writer) : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-9.%20DBWn(DB%20Writer).md)
- 1-10. LGWR(Log Writer) : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-10.%20LGWR(Log%20Writer).md)
- 1-11. CKPT(Checkpoint Process) : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-11.%20CKPT(Checkpoint%20Process).md)
- 1-12. SMON(System Monitor Process) : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-12.%20SMON(System%20Monitor%20Process).md)
- 1-13. PMON(Process Monitor) : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-13.%20PMON(Process%20Monitor).md)
- 1-14. ARCn(Archive Process) : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/1-14.%20ARCn(Archive%20Process).md)

### 2. 저장 영역 구조
- 2-1. 데이터베이스 저장 영역 구조 : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/2-1.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4%20%EC%A0%80%EC%9E%A5%20%EC%98%81%EC%97%AD%20%EA%B5%AC%EC%A1%B0.md)
- 2-2. 논리적 / 물리적 데이터베이스 구조 : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/2-2.%20%EB%85%BC%EB%A6%AC%EC%A0%81%2C%20%EB%AC%BC%EB%A6%AC%EC%A0%81%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4%20%EA%B5%AC%EC%A1%B0.md)

### 3. Startup & Shutdown
- 3-1. Startup 의 4가지 단계 : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/3-1.%20Startup%20%EC%9D%98%204%EA%B0%80%EC%A7%80%20%EB%8B%A8%EA%B3%84.md)
- 3-2. Shutdown 의 4가지 옵션 : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/3-2.%20Shutdown%20%EC%9D%98%204%EA%B0%80%EC%A7%80%20%EC%98%B5%EC%85%98.md)
- 3-3. 그 외의 방법들 : Startup Force / srvctl : [[보기]](https://github.com/corvina1208/Oracle_Admin/blob/main/3-3.%20%EA%B7%B8%20%EC%99%B8%EC%9D%98%20%EB%B0%A9%EB%B2%95%EB%93%A4%20%3A%20Startup%20Force%2C%20srvctl.md)

### 4. Parameter File 관리
- 4-1. 초기화 파라미터 관리 : SPFILE & PFILE : [[보기]](https://rebel-lord-f41.notion.site/SPFILE-PFILE-09c6cc8a05b1424e9693540405cb42ed?pvs=4)
- 4-2. 초기화 파라미터 관리 : System Level / Session Level : [[보기]](https://rebel-lord-f41.notion.site/System-Level-Session-Level-0f88b5311ab24b46ab616d52db83df56?pvs=4)

### 5. Tablespace 관리
- 5-1. Tablespace 에 대한 이해 : [[보기]](https://rebel-lord-f41.notion.site/Tablespace-5a6af05bebca42919d52b5abcfbb5a82?pvs=4)
- 5-2. Tablespace 생성 : [[보기]](https://rebel-lord-f41.notion.site/Tablespace-e1d80a1cfbc94f138c6de064b7231dfa?pvs=4)
- 5-3. Tablespace 삭제 : [[보기]](https://rebel-lord-f41.notion.site/Tablespace-d8780304356d41fa996aa2cab24c7342?pvs=4)
- 5-4. Tablespace 공간 추가 : [[보기]](https://rebel-lord-f41.notion.site/Tablespace-ff72bee1ac5d43ae9967f76644cd4ead?pvs=4)
- 5-5. Default Tablespace : [[보기]](https://rebel-lord-f41.notion.site/Default-Tablespace-525e6d24f2164cd391944c00c2f5e0bd?pvs=4)
- 5-6. 과도한 정렬 작업을 위한 Temporary Tablespace : [[보기]](https://rebel-lord-f41.notion.site/Temporary-Tablespace-8a530a8ba549456090e9c4b44e979d86?pvs=4)
- 5-7. 과도한 DML 작업을 위한 Undo Tablespace : [[보기]](https://rebel-lord-f41.notion.site/DML-Undo-Tablespace-58604cbf0665423fb485274a5fb0bdbd?pvs=4)
- 5-8. Data file 이름 변경 / 위치 이동 : [[보기]](https://rebel-lord-f41.notion.site/Data-file-b3e806ce88b84b21b8c88e769d54571a?pvs=4)
- 5-9. Tablespace 의 Segment 관리 방법 : [[보기]](https://rebel-lord-f41.notion.site/Tablespace-Segment-74a655c756b14e6bb30dc41144f1fe83?pvs=4)
- 5-10. OMF(Oracle Managed Files) : [[보기]](https://rebel-lord-f41.notion.site/OMF-Oracle-Managed-Files-171d1ebc049c438e9ab4d3ded87463ca?pvs=4)
- 5-11. Tablespace 생성 시 Extent 관리 방법 : [[보기]](https://rebel-lord-f41.notion.site/Tablespace-Extent-406e2653e1294b20a98601136b95d280?pvs=4)
- 5-12. Bigfile Tablespace : [[보기]](https://rebel-lord-f41.notion.site/Bigfile-Tablespace-f168ae90b230477fb3dbbe448da8d2bd?pvs=4)

### 6. Undo Tablespace 관리 🌟
- 6-1. Undo Data 에 대한 이해 : [[보기]](https://rebel-lord-f41.notion.site/Undo-Data-e70a2b1cf4ce4567b4088d6059b7c83c?pvs=4)
- 6-2. Undo Data / Redo Data : [[보기]](https://rebel-lord-f41.notion.site/Undo-Data-Redo-Data-6977877fac6c4c2c93877c58f1cae025?pvs=4)
- 6-3. Undo Data 자동 관리 : [[보기]](https://rebel-lord-f41.notion.site/Undo-Data-ecabe79c28504cecb570a94f6e0191c1?pvs=4)
- 6-4. Undo Retention : [[보기]](https://rebel-lord-f41.notion.site/Undo-Retention-90ade0953e154cbc9a7566fedb147c10?pvs=4)
- 6-5. ORA-01555 snapshot too old : [[보기]](https://rebel-lord-f41.notion.site/ORA-01555-snapshot-too-old-28f61ab2a8e64aee9572c177dbb0950a?pvs=4)

### 7. Network 관리
- 7-1. Oracle Net Service : [[보기]](https://rebel-lord-f41.notion.site/Oracle-Net-Service-2df246477cdd4ddf91c8c4ce2f93b5c3?pvs=4)
- 7-2. SQL developer & DBeaver 접속 방법 : [[보기]](https://rebel-lord-f41.notion.site/SQL-developer-DBeaver-165eafd646ad454b9e694b4385688623?pvs=4)
- 7-3. Oracle Network 관리 도구 : [[보기]](https://rebel-lord-f41.notion.site/4c103d89a28b483d8b8445b3639671e1?pvs=4)
- 7-4. Oracle Server 접속 방식 : [[보기]](https://rebel-lord-f41.notion.site/9a4ba922748649dca609f5c302647b0b?pvs=4)
- 7-5. Oracle 접속 불가 시 확인해야할 사항 : [[보기]](https://rebel-lord-f41.notion.site/5ef42b115ad944ed880a1cfa30202b82?pvs=4)

### 8. User 관리
- 8-1. User 생성 방법 : [[보기]](https://rebel-lord-f41.notion.site/User-ce44917d16ea44598c2c01b7db956caa?pvs=4)
- 8-2. User 인증 방법 3가지 : [[보기]](https://rebel-lord-f41.notion.site/User-3-fc1d50dc057045d69b1428ae69ebcb4d?pvs=4)
- 8-3. User 보안 : [[보기]](https://rebel-lord-f41.notion.site/User-fa4e63bb52124503be2aa3e043d7ab49?pvs=4)
- 8-4. 오라클 DB 관리자 인증 방법 2가지 : [[보기]](https://rebel-lord-f41.notion.site/DB-2-397a7f7f974541edbfeaa5d003974e3f?pvs=4)
- 8-5. 오라클 DB 권한 종류 2가지 : [[보기]](https://rebel-lord-f41.notion.site/DB-2-7e4a2b76185746d29d0ee7624ee8ac63?pvs=4)
- 8-6. with admin option 개념과 사용 : [[보기]](https://rebel-lord-f41.notion.site/with-admin-option-24f11ac908754523af08df48ade03c45?pvs=4)
- 8-7. with grant option 개념과 사용 : [[보기]](https://rebel-lord-f41.notion.site/with-grant-option-fa4ebf903ecf426a8c43af7c9194c737?pvs=4)
- 8-8. Role 개념과 사용 : [[보기]](https://rebel-lord-f41.notion.site/Role-20b7322280be4a32885d64610872dbdf?pvs=4)

### 9. Resource Manager
- 9-1. Resource Manager 개념과 구현 : [[보기]](https://rebel-lord-f41.notion.site/Resource-Manager-7a2cbce70acb40b49707d0b68c762bce?pvs=4)
- 9-2. CPU 사용 제한 : [[보기]](https://rebel-lord-f41.notion.site/CPU-f8e3a1d7ef184f7c8c5a8c6b9c9dbb99?pvs=4)
- 9-3. 병렬도 제한 : [[보기]](https://rebel-lord-f41.notion.site/15f0867258e64bb3be273e2ccc8af3a2?pvs=4)
- 9-4. 악성 SQL 수행 제한 : [[보기]](https://rebel-lord-f41.notion.site/SQL-4e3cedc1cd4943ffa3fab7841f4e48af?pvs=4)

### 10. Data Migration 🌟
- 10-1. Data Migration 3가지 방법 : [[보기]](https://rebel-lord-f41.notion.site/Data-Migration-3-c0a47b3613594e7cb74e1724c0b01d97?pvs=4)
- 10-2. Direct Load Insert : [[보기]](https://rebel-lord-f41.notion.site/Direct-Load-Insert-88c81976aa934bb4a87ae6d720e33f51?pvs=4)
- 10-3. Direct Path Insert : [[보기]](https://rebel-lord-f41.notion.site/Direct-Path-Insert-SQL-Loader-csv-15c4be38d6bb4b5cba8b622fd7101d87?pvs=4)
- 10-4. 테이블 생성 스크립트 추출 : [[보기]](https://rebel-lord-f41.notion.site/2c346500a8f348e4afcc54436446c9ae?pvs=4)
- 10-5. Export / Import : Table Level : [[보기]](https://rebel-lord-f41.notion.site/Export-Import-Table-Level-6eae4deec4aa4207bda101baf8977389?pvs=4)
- 10-6. Export / Import : User Level : [[보기]](https://rebel-lord-f41.notion.site/Export-Import-User-Level-2a8bdc8f2df140448cceee4e2a703c14?pvs=4)
- 10-7. Export / Import : Tablespace Level : [[보기]](https://rebel-lord-f41.notion.site/Export-Import-Tablespace-Level-87835201ba694afca4713ca216f99872?pvs=4)
- 10-8. Export / Import : Database Level : [[보기]](https://rebel-lord-f41.notion.site/Export-Import-Database-Level-6122ad921a7241e48266cfa7fa6a5294?pvs=4)
- 10-9. Data Pump : Table Level : [[보기]](https://rebel-lord-f41.notion.site/Data-Pump-Table-Level-1e9737d7d5a74e9883cb822f7d3123f0?pvs=4)
- 10-10. Data Pump : User Level : [[보기]](https://rebel-lord-f41.notion.site/Data-Pump-User-Level-1cf5ab9e032f4b069b6a390cc76764b6?pvs=4)
- 10-11. Data Pump : Tablespace Level : [[보기]](https://rebel-lord-f41.notion.site/Data-Pump-Tablespace-Level-2c173749b21943ad9896a06266774592?pvs=4)
- 10-12. 고수들의 Data Migration 방법 : [[보기]](https://rebel-lord-f41.notion.site/Data-Migration-79f68e7085514bb48ba05d13d5cddfe1?pvs=4)
- 10-13. External Table 생성 : SQL*Loader & Pump : [[보기]](https://rebel-lord-f41.notion.site/External-Table-SQL-Loader-Pump-5081e88f76434c64b330274efe4413bd?pvs=4)

### 11. 공간 관리 🌟
- 11-1. DB reorg : [[보기]](https://rebel-lord-f41.notion.site/DB-reorg-c2de10bb60444737bc69c1c0275b0c28?pvs=4)
- 11-2. 테이블 압축 : [[보기]](https://rebel-lord-f41.notion.site/d5f43f7cb0b94b9294cadffb7c40a08c?pvs=4)
- 11-3. Deferred Segment : [[보기]](https://rebel-lord-f41.notion.site/Deferred-Segment-520ba1360b2548258ce1a63283c288fd?pvs=4)
- 11-4. ASM(Automatic Storage Managment) : [[보기]](https://rebel-lord-f41.notion.site/ASM-Automatic-Storage-Managment-ebc3ee5de58743cbbc3a186f7d83c9f5?pvs=4)
