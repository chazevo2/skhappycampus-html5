# skhappycampus-html5
html5 study

get 요청 : 
  => url?key=요청데이터&key=데이터 
  => 길이 255자 이내, 보안 취약, 검색요청
  ex)http://localhost:8070/sample/form_sample.html?memberId=abc&memberPw=abc&grade=%EC%9D%BC%EB%B0%98%ED%9A%8C%EC%9B%90&gender=%EB%82%A8&hobby=Java%EA%B3%B5%EB%B6%80&hobby=html%EA%B3%B5%EB%B6%80&hobby=%EB%A7%9B%EC%A7%91&moblie1=010&mobile2=1234&mobile3=1234#

post 요청 : 
	=> 요청데이타가 body에 첨부되어 전송
	=> 길이 제한 없음, 사용자가 볼 수 없음, 보안데이터 전송
	ex)http://localhost:8070/sample/form_sample.html#
