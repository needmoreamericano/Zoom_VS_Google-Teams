# Zoom_VS_Google-Teams
Two massive Video Meeting platform Zoom &amp; Google Teams - What are their competitive advantage and shortage? Analyzing through Goolge Playstore Review Data

Covid로 인해 비대면 회의 및 수업이 많아지며 이 서비스를 제공하는 플랫폼이 급성장을 이뤘고 선두주자로는 Zoom과 Google Teams로 굳혀졌습니다.
필자도 수업과 회의가 있는 날이면 하루에 6시간 이상 해당 플랫폼을 사용하는데 두 플랫폼의 어떤 특성이 고객의 다양한 만족도의 양상으로 이어지는지 분석해보고자 했습니다.
(해당 내용은 KUBS Social Meadia Analytics course에서 필자를 포함한 team에서 진행했습니다.)

<데이터 수집>

1. 북미서버 Google PlayStore의 리뷰 및 rating 데이터를 Beautiful Soup 패키지를 이용해 크롤링

<분석 방법>

1. Sentiment Analysis : 리뷰 데이터의 감정 분석을 통해 실제 긍정 또는 부정의 감정이 rating으로 이어지는지 검증함

2. Clustering : 본격적인 각 플랫폼의 어떤 특성이 고객의 만족도를 결정하는지 분석하기 위해 시행, 두 플랫폼이 겹치는 cluster도 존재했으나 그렇지 않은 cluster는 각 플랫폼의 차별점으로 분류

3. 1번의 검증과 2번의 분류가 끝난 후 실제 플랫폼이 제공하는 서비스의 특성이 맞는지 확인하고 issue는 실제로 발생하는지 커뮤니티를 통해 다시 확인
