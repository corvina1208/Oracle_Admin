
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

### 6. Undo Tablespace 관리
- Undo Data 에 대한 이해 : [[보기]](https://rebel-lord-f41.notion.site/Undo-Data-e70a2b1cf4ce4567b4088d6059b7c83c?pvs=4)
- Undo Data / Redo Data : [[보기]](https://rebel-lord-f41.notion.site/Undo-Data-Redo-Data-6977877fac6c4c2c93877c58f1cae025?pvs=4)
- Undo Data 자동 관리 : [[보기]](https://rebel-lord-f41.notion.site/Undo-Data-ecabe79c28504cecb570a94f6e0191c1?pvs=4)
- Undo Retention : [[보기]](https://rebel-lord-f41.notion.site/Undo-Retention-90ade0953e154cbc9a7566fedb147c10?pvs=4)
- ORA-01555 snap shot too old : [[보기]](https://rebel-lord-f41.notion.site/ORA-01555-snapshot-too-old-28f61ab2a8e64aee9572c177dbb0950a?pvs=4)
