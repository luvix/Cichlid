# Cichlid
**웹 앱 전용 인터넷 브라우저**  
Internet Browser for Web Application

웹 어플리케이션을 독립 및 설치된 프로그램처럼 작동하게 합니다.  
확장자를 가진 링크 파일을 열면 자동으로 해당 앱에 맞춰진 시클리드를 실행합니다.

- Desktop/Laptop Add-on. It is for Windows or Mac.
- It is a program to open any link. file link, web link, absolute path file link, relative path file link, hard link, soft link, any link a computer can open.
- It will base on Node library. But It should be light, so may be out-of-node.
- It will support chromium extension.

# 문제인식

## 구글 드라이브, 시놀로지 나스를 쓸 때면 바로가기를 열지 못하는게 너무 아쉬웠다.
바로가기가 없으면 중복되는 파일이 너무 많다.

## 구글 독스, 드롭박스 페이퍼를 보면 .gdocs, .gsheet, .gslides, .paper 등 여러 확장자는 지원해주긴 한데. 이런 서비스들을 보다 쉽게 열고 편집할 수 있으면 좋겠다.
특히 Dropbox Paper! 이건 '크롬에서 '창으로 열기'를 해도 페이지르 열 때마다 너무 구리게 나와서 불편했다.

![chrome 창으로 열기](https://user-images.githubusercontent.com/16158188/155846899-c72a98dd-96a0-41ff-b157-11fdcb8f93ac.png)

열 때는 한 페이지만 열 수 있고, 다른 페이지를 열 때마다 다른 창에 몰려서 열린다.  
창으로 열기는 결국 한 페이지만 창을 열기고, 다른 페이지는 일반 크롬 브라우저에서 열린다.

## 요즘 브라우저 너무 무거운데 모든 애드온을 다 켜기엔 메모리가 아깝다
하나 딱 키려고 하면 그냥 무지성으로 전부 다 켜지잖아. 그게 싫다.

## 어차피 Chromium 기반이라면, 크롬 확장 프로그램도 붙여서 쓰고 싶다
gmail 쓰는데 크롬 확장 프로그램을 못 쓰는 것도 아깝잖아.

# 지원 계획
## Web Application Services

### .paper for Dropbox Paper

### .notion for Notion
이건 가능하면 notion 계정 동기화를 하면 디렉토리 구조를 짠 하고 만드는 것도 좋을 것 같아

### .ipynb for Jupyter Notebook

### .odoc, .sheet for Synology Drive

### .gsheet, .gdoc, gslides for Google Drive

### (미정) .docx, .pptx, .xlsx for officeless user
Office 365를 구독하지 않았지만 그냥 MS 계정이 있어서 office 무료 버전을 사용할 수 있는 사람

## 조직 내 SaaS 최적화 서비스
Notion, Google Drive, Dropbox, Synology 등 많은 SaaS가 조직 차원에서 제공되는 경우가 있다.
사용자는 구분해야할 필요가 있다.
그래서 *눈으로 보면 바로 구분 가능한 조직 서비스용 아이콘*을 고려중이다.  조직 아이콘을 뱃지처럼 달던가 조직아이콘에 서비스 아이콘을 달던가 하는 방식같은 걸로 생각중이다.
