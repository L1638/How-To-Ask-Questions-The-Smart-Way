# 똑똑하게 질문하는 법

원문 링크: http://www.catb.org/~esr/faqs/smart-questions.html

Revision 3.10 버전을 기준으로 작성되었습니다.

여러분의 참여가 큰 도움이 됩니다.

Issues와 Pull requests를 통해 더 나은 번역에 함께 해주세요.

## 목차

  * 면책 조항
  * 서론
  * 질문하기 전에
  * 질문할 때
    * 어느 포럼에 질문할 지 신중히 고르세요
    * Stack Overflow
    * 웹 및 IRC 포럼
    * 두 번째 단계로, 프로젝트 메일링 목록을 사용하세요
    * 의미있고 구체적인 제목을 사용하세요
    * 답변하기 쉽도록 하세요
    * 명확하고, 문법적으로 옳으며, 오타가 없도록 작성하세요
    * Send questions in accessible, standard formats
    * 당신이 마주친 문제 상황에 대한 정확한 정보를 제공하세요
    * 양으로 승부하지 마세요
    * 버그를 찾았다고 성급히 주장하지 마세요
    * 당신이 자신을 낮춘다고 우리가 숙제를 대신 해주지는 않을 겁니다
    * 당신의 추측 말고 실제로 발생한 현상만 알려주세요
    * 발생한 현상을 시간 순서대로 알려주세요
    * 과정이 아니라 당신이 원하는 목표를 알려주세요
    * 개인 이메일로 답변을 요구하지 마세요
    * 명시적으로 질문하세요
    * 당신이 작성한 코드에 대해 질문할 때
    * 숙제를 올리지 마세요
    * 쓸데없는 문구는 넣지 마세요
    * 당신이 진짜 급하더라도 "급합니다" 같은 문구는 넣지 마세요
    * 예의를 갖추는 것은 절대로 손해보는 일이 아닙니다
    * 문제가 해결되었다면 이를 알려주세요
  * 답변을 이해하는 법
    * RTFM과 STFW: How To Tell You've Seriously Screwed Up
    * 답변이 이해가 안 간다면...
    * 답변이 무례하게 느껴진다면
  * 루저처럼 반응하지 않기
  * 하지 말아야 할 질문
  * 좋은 질문과 나쁜 질문
  * 당신이 답변을 받지 못한다면
  * 도움이 되는 방식으로 질문하는 법
  * 연관 자료
  * 감사의 말

## 면책 조항

많은 프로젝트 웹사이트에서 도움 받는 방법 섹션에 이 문서로의 링크를 걸어 놓습니다. 좋습니다. 그게 이 문서의 목적이니까요. 하지만 당신이 프로젝트 웹사이트 운영자이며 이 문서로 링크를 걸고자 한다면, 제발 *우리는 당신 프로젝트의 안내 데스크가 아니라는 것*을 링크 근처에 눈에 띄게 표시해주세요.

그러한 공지가 없으면, 우리는 이 문서를 작성했다는 이유만으로 우리가 온 세상의 기술적인 문제를 다 해결해야 한다고 생각하는 바보들에게 끊임없이 시달리게 된다는 것을 배웠습니다.

만약 당신이 도움이 필요하기 때문에 이 문서를 읽게 되었고, 이 문서의 저자들이 당신을 도울 수 있을 것이라고 생각했다면, 바로 *당신*이 우리가 방금 언급한 바보인 겁니다. *우리*한테 질문하지 마세요. 우리는 당신을 무시할 겁니다. 우리가 이 문서를 작성하는 건 당신이 쓰는 소프트웨어 혹은 하드웨어에 대해 잘 아는 사람들에게서 도움을 받는 방법을 알려주기 위해서인데, 그 "잘 아는 사람"은 99.9%의 경우에 우리가 아닙니다. 당신이 이 문서의 저자 중 한 명이 당신이 원하는 전문가라는 것을 *확실히* 아는 것이 아니라면, 모두의 행복을 위해 제발 우리를 가만히 내버려두세요.

## 서론

[해커](http://www.catb.org/~esr/faqs/hacker-howto.html)의 세계에서 기술적인 질문에 대해 당신이 받게 되는 답변의 종류는 당신이 질문을 하는 방식만큼이나 답변을 만드는 난이도에 달려 있습니다. 이 가이드는 당신이 만족스러운 답변을 얻을 가능성이 높아지도록 질문하는 방법을 알려줍니다.

오픈 소스의 사용이 널리 퍼지면서, 질문에 대한 좋은 답변을 해커뿐 아니라 숙련된 사용자에게서도 많이 받을 수 있습니다. 이건 좋은 일이죠. 사용자는 초보자들이 자주 겪는 실수에 대해 조금 더 관대한 경향이 있습니다. 그러나 답변자가 숙련된 사용자더라도 이 글에서 제시하는 방법으로 해커처럼 대하는 것이 일반적으로 유용한 답변을 얻을 수 있는 가장 효과적인 방법입니다.

가장 먼저 이해해야 할 것은 해커는 어려운 문제와 생각을 불러일으키는 좋은 질문을 정말 좋아한다는 것입니다. 질문을 싫어했다면 굳이 여기에 있지 않았을 겁니다. 당신이 흥미로운 질문을 준다면 정말 고마울 겁니다. 좋은 질문은 상쾌한 자극이고 선물이니까요. 좋은 질문은 우리의 이해를 증진시키고, 생각해보지 않았거나 알아차리지 못했던 문제를 드러냅니다. 해커들 사이에서 "좋은 질문입니다!" 라는 말은 진심 어린 칭찬입니다.

그럼에도 불구하고 해커는 간단한 질문에도 적대감이나 오만함을 드러내며 답변한다는 이미지가 있습니다. 어떨 때는 우리가 초보자와 이 분야를 처음 접하는 사람만 보면 무례하게 대하는 것처럼 보이기도 합니다. 하지만 이건 사실이 아닙니다.

우선 우리는 당연히 질문하기 전에 스스로 생각도 해보지 않는 사람과 숙제를 스스로 하지도 않는 사람에게 적대적입니다. 그런 사람들은 그저 시간 낭비입니다. 받기만 하고 주는 건 없으며, 우리가 더 흥미롭고 대답할 가치가 있는 다른 질문에 쓸 수 있었을 시간을 빼앗습니다. 우리는 이런 사람들을 "루저"라고 부르기로 약속했어요.

당장 우리가 만든 프로그램을 쓰는 것이 중요하고 기술적인 세부 사항을 배우는 것에는 큰 관심이 없는 사람이 많다는 걸 우리도 잘 압니다. 대부분의 사람들에게 컴퓨터는 그저 도구일 뿐입니다. 해야 할 더 중요한 일이 있고 살아야 할 삶이 있지요. 우리는 그걸 존중하며 우리가 열광하는 기술적인 문제에 모든 사람들이 관심을 가질거라 기대하지 않습니다. 그렇지만 우리는 그런 관심을 가지고 문제 해결에 적극적으로 참여하고자 하는 사람들에 맞추어 답변을 할 겁니다. 그리고 그건 안 바뀔겁니다. 바뀌어서는 안되고요. 만약 바뀐다면 우리는 우리가 가장 잘 하는 일에 약해지게 될겁니다.

우리는 (대부분) 자원 봉사자입니다. 우리는 바쁜 삶 와중에 시간을 내어 질문에 답하고, 때로는 넘쳐나는 질문에 압도됩니다. 그래서 우리는 무자비하게 걸러냅니다. 구체적으로, 우리는 루저로 보이는 사람들의 질문을 걸러서 대부분의 시간을 위너의 질문에 효율적으로 답변할 수 있도록 합니다.

이러한 태도가 불쾌하거나, 거만하거나 혹은 잘난 체하는 것처럼 보인다면 당신의 가정을 다시 확인하세요. 우리는 당신에게 납작 엎드리라고 말하는 게 아닙니다. 사실 우리 대부분은 당신이 적절한 노력을 기울인다면 우리의 문화로 반갑게 맞이하고 동등하게 대할 것입니다. 하지만 스스로를 도우려 하지 않는 사람을 도우려 애쓰는 것은 우리에게 그저 비효율적일 뿐입니다. 모르는 건 괜찮지만, 바보같이 구는 건 괜찮지 않습니다.

그러니까 우리의 주목을 받기 위해 기술적으로 유능할 필요는 없지만, 유능함으로 이어지는 태도, 즉 주의 깊고, 사려 깊고, 관찰하고, 솔루션 개발에 적극적으로 참여하는 태도를 보여줄 필요는 있습니다. 당신이 이런 종류의 차별을 못 견디겠다면 우리에게 개인적으로 기부를 요구하는 대신 돈을 내고 상업적 지원을 받는 것을 추천합니다.

당신이 우리에게 도움을 청하기로 결정했다면, 루저가 되지 마세요. 루저처럼 보이지도 마세요. 빠르고 긍정적인 답변을 받는 가장 좋은 방법은 똑똑하고 자신감 있으며 그저 특정 문제에 대해 도움이 필요한 사람처럼 질문하는 것입니다.

(이 문서의 개선 요청은 언제든지 환영입니다. esr@thyrsus.com 또는 respond-auto@linuxmafia.com 으로 제안 사항을 보내주세요. 다만 이 문서는 네티켓에 대한 일반적인 가이드가 아니며, 기술 포럼에서 유용한 답변을 도출하는 것과 특별한 관련이 없는 제안은 일반적으로 거부합니다.)

## 질문하기 전에

기술적인 질문을 이메일이나 뉴스 그룹, 혹은 웹사이트 채팅창에 올리기 전에 다음을 수행하세요.

  1. 글을 올리기로 마음먹은 포럼의 아카이브나 메일링 리스트에 답이 있는지 먼저 검색하세요.
  2. 인터넷 검색을 통해 답이 나오는지 확인하세요.
  3. 매뉴얼에 답이 있는지 확인하세요.
  4. FAQ에 답이 있는지 확인하세요.
  5. 관찰과 실험을 통해 답을 찾을 수 있는지 확인하세요.
  6. 잘 아는 친구한테 물어보세요.
  7. 당신이 프로그래머라면, 소스 코드를 읽어보고 답이 나오는지 확인하세요.

질문할 때 당신이 이를 이미 했다는 사실을 알려주세요. 이를 통해 당신이 사람들의 시간을 낭비하는 게으름뱅이가 아니라는 걸 확인할 수 있습니다. 더 나은 방법은 당신이 이를 통해 무얼 배웠는지를 보여주는 겁니다. 우리는 답변에서 배울 수 있는 사람을 위해 답변하는 것을 좋아합니다.

당신이 얻은 오류 메시지를 그대로 구글(구글 그룹과 웹 페이지 포함)에 검색하세요. 어쩌면 오류를 수정하는 방법을 알려주는 문서 혹은 메일링 리스트를 바로 찾아낼 수도 있습니다. 그렇지 않더라도 이메일이나 뉴스 포스팅에서 도움을 요청할 때 "다음 문구를 구글에 검색해봤지만 유용한 결과를 얻지 못했습니다" 라고 말해주는 건 도움이 됩니다. 첫째로 어떤 검색어가 도움이 안되는지에 대한 정보를 제공해주며, 둘째로 당신이 사용한 검색어가 당신이 만든 글타래와 연결되어 비슷한 문제를 겪는 다른 사람들이 당신의 질문 및 답변 글타래로 안내받을 수 있도록 합니다.

천천히 하세요. 단 몇 초의 구글링으로 복잡한 문제가 풀릴거라 기대하지 마세요. 전문가에게 물어보기 전에 우선 FAQ를 읽고 이해해보고, 편히 앉아 긴장을 풀고 문제에 대해 생각해보세요. 당신이 얼마나 찾아보고 생각해봤는지는 질문에 다 드러납니다. 당신이 준비가 되어있다면 더욱 기꺼이 도와주려 할겁니다. 첫 번째 검색에서 답을 얻지 못했다고 (혹은 너무 과도하게 얻었다고) 바로 질문 폭격을 날리지 마세요.

질문을 차분히 정리하세요. 깊게 생각하세요. 성급하게 들리는 질문은 성급한 답변을 얻거나, 전혀 얻지 못합니다. 당신이 문제를 해결하기 위해 얼마나 많은 생각과 노력을 기울였는지 보여줄수록 실제로 도움을 받을 가능성이 높아집니다.

잘못된 질문을 하지 않도록 유의하세요. 잘못된 가정에 기반한 질문을 하면 해커 아무개씨는 당신에게 실제로 도움이 되지 않는, 하지만 질문 그 자체에 대한 답변을 해줄겁니다. 그리고 속으로 "멍청한 질문같으니..." 라고 생각하면서 당신이 실제로 필요한 답변이 아닌 질문 그 자체에 대한 답변을 얻는 경험을 통해 속쓰린 교훈을 얻기를 기대할 겁니다.

당신에게 답변을 받을 자격같은 게 있다고 착각하지 마세요. 그런 건 없습니다. 애초에 당신은 돈을 내고 서비스를 받고 있는 게 아닙니다. 당신이 답변을 받는다면, 그건 다른 이의 지식을 수동적으로 요구하는 것이 아니라 실질적이고 흥미롭고 생각을 불러 일으키는 질문을 통해 커뮤니티 전체의 경험에 기여했기 때문입니다.

반면에 당신이 해결책을 만드는 과정에 적극적으로 참여할 수 있다는 의지와 노력을 보여주는 것은 아주 좋은 시작입니다. "정확히 어떻게 해야 하는지 알려주세요." 같은 질문 보다는 "혹시 관련된 자료는 어디서 찾을 수 있나요?", "제 예시에서 빠진 게 뭐죠?", "어떤 사이트를 찾아봐야 하나요?" 같은 질문이 답변을 받을 가능성이 높습니다. 누군가 올바른 방향만 알려준다면 당신이 진정으로 이 과정을 마칠 의지가 있다는 것이 명확히 드러나기 때문입니다.

## 질문할 때

### 어느 포럼에 질문할 지 신중히 고르세요

어디에 질문을 올릴지 정말 잘 고르세요. 만약 당신이 아래와 같이 질문한다면, 당신은 무시당하거나 루저로 취급당할 가능성이 높습니다.
  
  * 다른 주제를 다루는 포럼에 질문을 올리는 경우
  * 고급 기술 질문을 다루는 포럼에 아주 기초적인 질문을 올리는 경우나 그 반대의 경우
  * 너무 많은 뉴스 그룹에 동일한 질문을 올리는 경우
  * 당신의 지인도 아니고 당신의 문제를 해결해줘야 할 책임도 없는 사람한테 개인적으로 이메일을 보내는 경우

해커는 그들의 커뮤니케이션 채널이 쓸모없는 글에 침식되지 않도록 잘못 올라온 질문은 날려버립니다. 그런 일이 당신에게 일어나길 원하진 않겠죠.

그러니 당연히 첫 번째 단계는 올바른 포럼을 찾는 겁니다. 다시 말하지만 구글(그리고 다른 웹 검색 방법들)과 친해지세요. 이를 이용해서 당신을 괴롭히고 있는 하드웨어 혹은 소프트웨어와 가장 연관된 프로젝트 웹 페이지를 찾아내세요. 보통 그 페이지에는 FAQ(Frequently Asked Questions: 자주 묻는 질문) 목록과 프로젝트 메일링 리스트, 그리고 아카이브의 링크가 있을 겁니다. 이 메일링 리스트는 당신 스스로의 노력 (당신이 방금 찾아낸 FAQ를 전부 읽어보는 것을 포함)을 통해서 답을 찾지 못했을 때 **마지막으로** 도움을 요청하러 갈 곳입니다. 프로젝트 웹 페이지에 버그 보고 절차, 혹은 그에 대한 링크가 있을 수도 있습니다. 그렇다면 그 절차를 따르세요.

당신이 익숙하지 않은 사람이나 포럼에 이메일을 보내는 건 가장 위험합니다. 유익한 웹 페이지를 만든 사람이라고 해서 그 사람이 당신의 무료 컨설턴트가 되길 원한다고 가정하지 마세요. 당신의 질문이 환영받을거라고 낙관적으로 생각하지 마세요. 확실하지 않다면, 다른 곳에 보내거나 그냥 아예 보내지 마세요.

웹 포럼, 뉴스 그룹 혹은 메일링 리스트를 고를 때, 이름만 가지고 판단하지 마세요. FAQ나 헌장을 찾아보고 당신의 질문이 실제로 다루어지는 곳이 맞는지 확인하세요. 글을 올리기 전에 백트래픽을 조금 읽어본담녀 그곳에서 일이 어떻게 돌아가는지 감을 잡을 수 있습니다. 미리 당신의 문제와 관련된 키워드를 뉴스 그룹이나 메일링 리스트 아카이브에서 검색해보는 것은 큰 도움이 될 겁니다. 이를 통해 답을 찾을 수도 있고, 그렇지 않더라도 질문을 정제하는 데 도움이 됩니다.

가능한 모든 도움말 채널에 글을 마구 써대지 마십시오. 이는 마치 공공장소에서 소리를 지르는 것과 같고, 사람들을 짜증나게 합니다. 부드럽게 접근하세요.

당신의 토픽이 뭔지 알아야 합니다. 흔히 하는 실수 중 하나는 유닉스 혹은 윈도우 프로그래밍 인터페이스를 둘 모두에서 사용할 수 있는 언어/라이브러리/툴 관련 포럼에 올리는 겁니다. 이게 왜 문제인지 이해가 안 간다면, 이해가 갈 때까지 질문을 올리지 마세요.

일반적으로, 같은 질문이라면 공개 포럼에 올리는 것이 비공개 포럼에 올리는 것보다 유용한 답변을 얻을 가능성이 더 큽니다. 여러 이유가 있는데, 우선 단순히 잠재적 답변자의 수에 차이가 있기 때문이고 그 다음으로 청중의 수가 다르기 때문입니다. 해커는 더 많은 사람에게 유용한 지식을 전달할 수 있기를 원하니까요.

숙련된 해커와 유명한 소프트웨어의 개발자들은 받지 않았어야 할 메시지의 홍수에 시달리고 있습니다. 어쩌면 당신의 메시지가 낙타의 등을 부러뜨리는 마지막 지푸라기가 될지도 모릅니다. 개인 이메일 계정에 쓸모없는 이메일이 너무 많이 와서 이를 견디지 못한 유명 프로젝트의 기여자들이 지원을 철회한 경우도 종종 있었습니다.

### 스택 오버플로우 (Stack Overflow)

**먼저** 검색하고 **그 다음에** Stack Exchange에 질문을 올리세요.

최근 몇 년동안 Stack Exchange 사이트는 기술 및 기타 질문에 답하는 주요 커뮤니티가 되었고, 심지어 이제는 많은 오픈 소스 프로젝트에서 선호하는 포럼이 되었습니다.

Stack Exchange를 살펴보기 전에 구글 검색부터 하세요. 구글은 실시간으로 색인을 만듭니다. 아주 높은 확률로 누군가가 이미 비슷한 질문을 했을 것이며, 많은 경우 Stack Exchange 사이트가 검색 결과 상단에 위치합니다. 구글 검색으로 아무 것도 못 찾았다면, 당신의 질문과 가장 관련 있는 특정 사이트에서 다시 검색하세요 (아래 참조). 태그 기능을 활용하면 검색 결과를 좁혀나갈 수 있습니다.

여전히 아무 것도 못 찾았다면, 가장 연관 있는 사이트에 질문을 게시하세요. 포맷팅 도구를 쓰세요. 특히 코드를 올리는 경우라면, 반드시 포맷팅 도구를 쓰세요. 그 다음, 질문의 내용과 관계가 있는 태그를 추가하세요(당신이 문제를 겪고 있는 프로그래밍 언어, 운영체제 혹은 라이브러리). 더 많은 정보를 요청하는 댓글이 달린다면, 질문 글 수정을 통해 해당 내용을 추가하세요. 어느 답변이든 도움이 되었다면 추천 버튼을 눌러주세요. 어떤 답변이 당신 문제에 대한 해결책을 주었다면, 투표 버튼 아래에 있는 체크 버튼을 눌러 답변을 채택하세요.

Stack Exchange는 100개가 넘는 사이트로 성장했지만, 많은 경우 당신은 아래에 소개한 곳에 질문을 올리게 될 겁니다.

  * Super User는 범용 컴퓨팅에 관한 질문을 올리는 곳입니다. 당신의 질문이 코드나 프로그램에 관한 것이 아니라 단순히 네트워크 연결을 통해 작동하는 경우라면 아마도 여기에 올리는 게 맞을 겁니다.
  * Stack Overflow는 프로그래밍에 관한 질문을 올리는 곳입니다.
  * Server Fault는 서버와 네트워크 관리에 대한 질문을 올리는 곳입니다.

안드로이드, 우분투, TeX와 LaTeX, SharePoint 등의 프로젝트는 이를 위한 자체 사이트를 가지고 있습니다. Stack Exchange 사이트에서 최신 목록을 확인하세요.

### 웹 및 IRC 포럼

Your local user group, or your Linux distribution, may advertise a Web forum or IRC channel where newbies can get help. (In non-English-speaking countries newbie forums are still more likely to be mailing lists.) These are good first places to ask, especially if you think you may have tripped over a relatively simple or common problem. An advertised IRC channel is an open invitation to ask questions there and often get answers in real time.

In fact, if you got the program that is giving you problems from a Linux distribution (as is common today), it may be better to ask in the distro's forum/list before trying the program's project forum/list. The project's hackers may just say, “use our build”.

Before posting to any Web forum, check if it has a Search feature. If it does, try a couple of keyword searches for something like your problem; it just might help. If you did a general Web search before (as you should have), search the forum anyway; your Web-wide search engine might not have all of this forum indexed recently.

There is an increasing tendency for projects to do user support over a Web forum or IRC channel, with e-mail reserved more for development traffic. So look for those channels first when seeking project-specific help.

In IRC, it's probably best not to dump a long problem description on the channel first thing; some people interpret this as channel-flooding. Best to utter a one-line problem description in a way pitched to start a conversation on the channel.

### 두 번째 단계로, 프로젝트 메일링 목록을 사용하세요

When a project has a development mailing list, write to the mailing list, not to individual developers, even if you believe you know who can best answer your question. Check the documentation of the project and its homepage for the address of a project mailing list, and use it. There are several good reasons for this policy:

Any question good enough to be asked of one developer will also be of value to the whole group. Contrariwise, if you suspect your question is too dumb for a mailing list, it's not an excuse to harass individual developers.

Asking questions on the list distributes load among developers. The individual developer (especially if he's the project leader) may be too busy to answer your questions.

Most mailing lists are archived and the archives are indexed by search engines. If you ask your question on-list and it is answered, a future querent could find your question and the answer on the Web instead of asking it again.

If certain questions are seen to be asked often, developers can use that information to improve the documentation or the software itself to be less confusing. But if those questions are asked in private, nobody has the complete picture of what questions are asked most often.

If a project has both a “user” and a “developer” (or “hacker”) mailing list or Web forum, and you are not hacking on the code, ask in the “user” list/forum. Do not assume that you will be welcome on the developer list, where they're likely to experience your question as noise disrupting their developer traffic.

However, if you are sure your question is non-trivial, and you get no answer in the “user” list/forum for several days, try the “developer” one. You would be well advised to lurk there for a few daysor at least review the last few days of archived messages, to learn the local folkways before posting (actually this is good advice on any private or semi-private list).

If you cannot find a project's mailing list address, but only see the address of the maintainer of the project, go ahead and write to the maintainer. But even in that case, don't assume that the mailing list doesn't exist. Mention in your e-mail that you tried and could not find the appropriate mailing list. Also mention that you don't object to having your message forwarded to other people. (Many people believe that private e-mail should remain private, even if there is nothing secret in it. By allowing your message to be forwarded you give your correspondent a choice about how to handle your e-mail.)

### 의미있고 구체적인 제목을 사용하세요

### 답변하기 쉽도록 하세요

### 명확하고, 문법적으로 옳으며, 오타가 없도록 작성하세요

### Send questions in accessible, standard formats

### 당신이 마주친 문제 상황에 대한 정확한 정보를 제공하세요

### 양으로 승부하지 마세요

### 버그를 찾았다고 성급히 주장하지 마세요

### 당신이 자신을 낮춘다고 우리가 숙제를 대신 해주지는 않을 겁니다

### 당신의 추측 말고 실제로 발생한 현상만 알려주세요

### 발생한 현상을 시간 순서대로 알려주세요

### 과정이 아니라 당신이 원하는 목표를 알려주세요

### 개인 이메일로 답변을 요구하지 마세요

### 명시적으로 질문하세요

### 당신이 작성한 코드에 대해 질문할 때

### 숙제를 올리지 마세요

### 쓸데없는 문구는 넣지 마세요

### 당신이 진짜 급하더라도 "급합니다" 같은 문구는 넣지 마세요

### 예의를 갖추는 것은 절대로 손해보는 일이 아닙니다

### 문제가 해결되었다면 이를 알려주세요

## 답변을 이해하는 법

### RTFM과 STFW: How To Tell You've Seriously Screwed Up

### 답변이 이해가 안 간다면...

### 답변이 무례하게 느껴진다면

## 루저처럼 반응하지 않기

## 하지 말아야 할 질문

## 좋은 질문과 나쁜 질문

## 당신이 답변을 받지 못한다면

## 도움이 되는 방식으로 질문하는 법

## 연관 자료

## 감사의 말
