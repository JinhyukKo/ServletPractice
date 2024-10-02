# ServletPractice

## URI
board
1. /
2. HelloServlet.java
3. form
   1. /
   2. response  

## Path
/Java Resources : Servlet

/src/main/webapp/ : root directory for Static resources

### [/](./src/main/webapp/index.jsp)
<img width="241" alt="Screenshot 2024-09-30 at 9 38 17 PM" src="https://github.com/user-attachments/assets/8c49685b-8f84-4662-8793-46978c12e2a7">

1. URL 클릭시 파라미터가없어 hello null
2. doGet, doPost 시 hello *name*

### [/form](./src/main/webapp/form/index.jsp)
<img width="355" alt="Screenshot 2024-10-01 at 1 24 57 PM" src="https://github.com/user-attachments/assets/d5146188-48a4-4436-ae88-39b3fea8626c">


#### [/form/response.jsp](./src/main/webapp/form/response.jsp)

<img width="1000" alt="Screenshot 2024-10-01 at 2 17 58 PM" src="https://github.com/user-attachments/assets/3f7ba63d-df9c-4428-a065-809d8f9ac1de">

1. 요청라인 TCP/IP정보
2. 헤더정보 (warning 헤더정보 value는 리스트가 없음)
3. name과 value로 담겨 보낸 form data그대로 전송

### /cookie

<img width="460" alt="Screenshot 2024-10-02 at 9 32 39 PM" src="https://github.com/user-attachments/assets/923130d9-874d-4e05-a4c9-d4c6cda52760">
<img width="422" alt="Screenshot 2024-10-02 at 9 34 03 PM" src="https://github.com/user-attachments/assets/aa11de61-c828-485e-ae54-0b5b7f9fa5ee">

1. by submitting form, you can add cookies.
2. /cookie/cookie.jsp adds the cookie information and redirect to the previous page
3. you can see the result!
