----------------------
# 0410 #
## LayoutEx ##

	*###article과 aside 정렬하는 게 어려웠음###
		*float:left; 값은 주니 본문, 사이드바, 바닥들이 이상한 모양으로 정렬이 됨
		* 바닥글에 footer {clear: both;}값을 줌, 바닥글은 해결.
		*이후 section 크기를 보기편하게 border값을 주고난뒤 article과 aside 사이즈를 구해서 다시 정렬, 이때 크기값을 구하기 쉽게  box-sizing: border-box;를 사용했더니 모양이 만들어짐 
		*이후section을 삭제 하니 또 모양이이상해져서 직접 선언으로 안보이게 숨김
