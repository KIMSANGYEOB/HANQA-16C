# GIT & SVN

> GIT 과 SVN 사용법에 대해 알아봅시다.

- [GIT](#git)
- [SVN](#svn)
  - [SVN 방 연결하기](#svn-방-연결하기)
  - [SVN 방 연결 해제하기](#svn-방-연결-해제하기)
  - [프로젝트 SVN에 올리기](#프로젝트-svn에-올리기)

## GIT

진행 X

## SVN

### SVN 방 연결하기

1. SVN Repository 탭 영역에서 우클릭 -> New -> Repository Location...
![](/images/2주차/SVN위치.png)  
1. `URL`, `User`, `Password` 에 대한 정보 입력  
(Save authentication 체크시 `User`, `Password` 정보 저장)  
![](/images/2주차/SVN정보입력.png)  
1. SVN Repository 탭에서 연결된 방의 정보를 확인  
![](/images/2주차/SVN방확인.png)  

### SVN 방 연결 해제하기

1. Navigator 탭에서 SVN방과 연결해제 할 프로젝트 선택 후 우클릭
1. Team -> Disconnect 클릭  
![](/images/2주차/svnDisconnect.png)  
1. **Also delete the SVN meta-information from the file systems** 선택하여 `Yes` 클릭  
![](/images/2주차/svn연결해제끝.png)

### 프로젝트 SVN에 올리기

1. Navigator 탭에서 프로젝트 우클릭
1. Team -> Share Project 클릭  
![](/images/2주차/svnshare.png)  
1. SVN 선택 -> Next > 클릭  
![](/images/2주차/shareproject.png)  
1. Use existing repository location 선택 후 자신이 올릴 SVN방 선택하여 `Finish` 클릭  
(원하는 SVN방이 없다면 [SVN 방 연결하기](#svn-방-연결하기) 처럼 진행)
![](/images/2주차/SVN올리기끝.png)  
1. **Comment**영역에 해당 프로젝트에 대한 코멘트 입력 후 `OK` 클릭  
![](/images/2주차/SVN코멘트.png)