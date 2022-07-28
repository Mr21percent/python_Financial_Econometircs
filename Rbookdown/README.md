**금융시계열분석(김명직 저)** 책을 python statsmodels 라이브러리를 활용하여 다시 공부중입니다.

book 올리는 법
- index.Rmd 파일은 필수
- bookdown::render_book()로 랜더링
- outline에서는 head (#) 중간에 빠진거 있으면 제대로 안나오지만, 책은 알아서 설정해주는거로 보임.
- output:
   html_document:
     number_sections: true
   pdf_document:
     number_sections: true 로 숫자 넣은거 생략함.