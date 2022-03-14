# jsp_8 : 날짜 요일 시간
      
![image](https://user-images.githubusercontent.com/37132897/158111182-21283aad-aefc-4d19-aa1d-dfe3a0260ddc.png)

      
      // 변수
      
      var date = new Date();
      
      // 변수 이용하여 날짜 요일 시간 출력
      
      document.write(date); // 1. 한국 표준시간
      
      document.write("<br>");
      
      document.write(date.getMonth()); // 2. 월, 0부터시작이라 +1 해줘야됨
      
      document.write("<br>");
      
      document.write(date.getDay()); // 3. 요일, 1부터 시작
      
      document.write("<br>");
      
      document.write(date.getDate()); // 4. 일
      
      document.write("<br>");
      
      document.write(date.getHours()); // 5. 시
      
      document.write("<br>");
