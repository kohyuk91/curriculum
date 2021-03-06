# 왜 리눅스를 사용하는가?
한국 및 국제적으로 대규모 VFX회사는 대부분 리눅스 시스템을 선호하며 현재 많이 사용중입니다.

![linux_map](http://i.imgur.com/Qfo8JXC.jpg)

## 리눅스를 사용하는 이유.
- 무료 : 비용절감
- 안정적
- 낮은 사양에서도 잘 돌아감.
- 개발자 친화적. 인하우스 툴을 제작, 배포하기 편리하다.
- 수많은 개발도구를 무료로 사용할 수 있다.
- 컴퓨터 사양이 낮아도 효율이 좋다. 다른 OS보다 실제 연산이 10~15% 빠른 소프트웨어들이 존재합니다.
    - https://twitter.com/themikepan/status/1070492631526830080?s=21
- 악성코드의 노출이 낮음.
- 대량셋팅이 용이함
- 네트워크 파일시스템 지원 : 회사가 경로를 셋팅하여 사용할 때 일괄적으로 통일해서 사용가능하다.
- 대량의 렌더팜, 서버 셋팅용이 : ssh, 가상화, 서버 매니징툴들이 많이 있습니다.
- 보안 : 소스코드가 공개되어있어서 비교적 빠른 보안업데이트가 나온다. 간혹 공개 소스를 분석하여 취약점을 악용하는 사용자도 있습니다. 보안뉴스에 관심을 가지고 사용하면 운용시 크게 도움이 됩니다.

## CentOS를 사용하는 이유
- Autodesk, Foundry 에서 Redhat, CentOS 계열의 리눅스에서 테스트합니다.
- Redhat은 Fedora 프로젝트를 통해서 테스팅하여 만들어집니다.
- CentOS는 Redhat이 배포되면 같은 코드를 그대로 사용합니다.

#### CentOS의 특징
- https://www.lesstif.com/pages/viewpage.action?pageId=20775405

#### 기업에서는..
이 강의는 인터넷이 연결된 환경에서 커리큘럼이 진행되도록 구성되었습니다.
하지만 많은 기업은 인트라넷 환경으로 구성되어있습니다.
이 점을 참고하여 진행해주세요.

## 매력
리눅스에는 수많은 개발도구들이 지원됩니다.
개발자들이 서로 협력하는 모델, 지원하는 개발툴들의 매력에 빠지게 된다면 어쩌면 당신도 다른 OS를 사용하지 못할 수 있어요.

## 각 소프트웨어 요구사항 Reference
- Autodesk : https://knowledge.autodesk.com/support/maya/learn-explore/caas/sfdcarticles/sfdcarticles/System-requirements-for-Autodesk-Maya-2018.html
- Foundry Nuke : https://www.foundry.com/products/nuke/requirements
- Foundry Katana : https://www.foundry.com/products/katana/requirements