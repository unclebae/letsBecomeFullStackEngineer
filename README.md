# [목록으로](https://github.com/unclebae/letsBecomeFullStackEngineer)

# 1장 풀스택 엔지니어로 거듭나기

# 풀 스택 엔지니어

필자가 처음 IT 업계를 공식적으로(?) 뛰어든 시기는 2002년 부터 입니다.
그때는 ASP, JSP, PHP와 같은 웹 프로그래밍 언어를 활용한 웹 개발이 본격적으로 꽃을 피우던 시기였습니다.
많은 개발자들이 기업 홈 페이지를 개발하고, 회원을 모집하고 웹을 통한 서비스 중심으로 서비스가 제공되었습니다. 
ASP, JSP, PHP 등과 같은 기술은, 페이지 내에서 HTML, CSS, JavaScript, 그리고 서버사이드 프로그래밍 코드까지 모두 삽입해서 개발을 하는 방식이었습니다.

이러한 방식은 동적 웹 어플리케이션을 개발하는데 있어 획기적인 방법이었고,  단순 이미지나, 정적 페이지만을 제공하던 방식에서 웹 페이지에 생동감을 불어넣는 작업이었습니다.

시간은 언제나 그렇듯이 문제가 있는 부분을 개선하고, 서비스의 안정성과 우수한 기능을 제공하기 위한 좀더 향상된 방향으로 발전하게 되었습니다. 

점점 서버사이드 개발의 비중이 커지게 되었고, 레이어 구성도 웹서버 > WAS > DB와 같이 컨텐츠와 동적 페이지를 분리하여 제공했습니다. 

AJAX 기술이 도입되면서 동적 컨텐츠를 렌더링 할 수 있게 되었고, 이후 웹 개발에 혁신을 가져 왔습니다. 

또한 서버 사이드는 EJB 라는 엔터프라이즈 자바 빈즈가 인기를 끌게되고, 기업들은 너도나도 엔터프라이즈 시스템을 개발하는데 노력을 했습니다.
하지만 EJB 가 가진 사싱은 매우 훌륭했지만, 통합 환경을 만드는데 너무 많은 리소스가 필요했고, 높은 진입장벽과 시스템 유지보수에 대한 어려움을 해결하지 못하는 일도 있었습니다. 

이후 로드존슨이 개발한 스프링 프레임워크는 EJB가 가지고 있던 복잡성을 완전히 해소하고, 업계 표준으로 자리 잡게 되었습니다. 지금은 스프링이 단연 가장 인기있는 웹 개발 프레임워크로 자리잡고 있습니다. 

최근에는 WAS에서 REST API 를 제공하고 WEB Server 에서는 정적 페이지와 컨텐츠등을 제공하는 방식으로 시스템이 API 화 되었습니다. 
클라이언트 사이드 서버의 리소스를 API 를 통해서 획득하고, 획득된 정보를 화면 변경없이 렌더링을 수행하여 빠른 피드백을 제공하고 있습니다. 이러한 방식의 웹 어플리케이션을 SPA(Single Page Application) 이라고 부릅니다. 

SPA이 대표적인 프레임워크로 React.js는 Facebook 에서 오픈소스화 했으며, 가장 인기있는 프런트엔드 프레임워크로 자리 잡았습니다. 
Angular.js 는 복잡성, 확정성의 문제를 해결하여 최근에는 Angular 로 그 이름을 바꾸었고, 구글에서 매니지먼트를 해주고 있는 프런트엔드 프레임워크입니다. 
최근에는 Vue.js 가 떠오르는 다크 호스로, 이미 Angular 을 제치고, React.js 를 위협하는 프레임워크로 부상하고 있습니다. 

최근 개발에 가장큰 변화를 가져온 것은 스마트폰을 중심으로한 모바일 어플리케이션이 주류를 이루었고 이러한 앱들은 안드로이드, iOS, 모바일 웹, PC 웹 등 다양한 형태로 개발 되고 있습니다. 

최근 IoT 의 확대, 5G 등으로 인해서 엣지 컴퓨팅등 시스템 아키텍처는 더욱 복잡해지고 있습니다. 

이러한 시점에서 풀 스택 엔지니어의 가치는 더욱 중요하게 평가되고 있습니다. 

풀 스택 개발자라는 용어는 페이스북 개발자들에 의해서 처음 사용되었습니다. 
풀 스택 엔지니어란 프런트 엔드 개발 기술에서 부터, 서버사이드 기술까지 모두 섭렵한 개발자를 의미합니다. 
한 때는 프런트엔드 개발과 백엔드 개발 기술을 동시에 할 줄 아는 사람들을 이야기하였으나, 최근 시스템 복잡도가 증가하고, 요구사항의 수준도 높아지면서, 프런트엔드, 백엔드, 시스템, 네트워크, 보안, 마이크로서비스 아키텍처 등 풀스택 개발자로써 알아야하는 기술이 더욱 그 깊이와 넓이가 확대되고 있습니다.

한 가지 해두고 싶은 것이 있다면, 위에서 언급한 기술을 모두 섭렵한에서 오해가 없길 희망합니다. 
풀 스택 개발자가, 모바일 앱 개발부터 서버사이드 개발 운영 모두를 완벽하게 해야한다는 것으로 오해하지 않아야 합니다. 

현재 나와 있는 모든 기술을 이해하고 사용하는 것은 현실상으로 거의 불가능한 이야기 입니다. 
그러므로 자신이 전문으로 할 수 있는 클라이언트 사이드 기술과 서버사이드 기술을 이용해서 전체 시스템을 설계하고 개발 할 줄 아는 사람으로 정의할 필요가 있습니다. 

## 풀 스택 엔지니어가 알아야하는 기술

풀 스택 엔지니어 가 알아야하는 기술을 프런트엔드, 백엔드, 그리고 DevOps의 관점으로 한번 알아 보겠습니다. 
단 여기서는 웹 프로그래밍으로 범위를 한정하여 설명 하겠습니다.

### 프런트엔드 기술:
* Basic:
    * HTML
    * CSS
    * JavaScript
* Package Manager
    * npm
    * yarn
* CSS Pre Process
    * SASS
    * LESS
* CSS Framework
    * Bootstrap
    * Materialize CSS
    * Semantic UI
* Build Tools
    * Webpack
    * gulp
* Framework
    * React.js
        * StateManagement
            * Redux
            * MobX
    * Angular
        * StateManagement
            * RxJS
            * ngrx
    * Vue.js
        * StateManagement
            * Vuex
* Service Side Rendering
    * React.js
        * Next.js
    * Angular
        * Universal
    * Vue.js
        * Nuxt.js

### 백엔드 기술
* WEB Server
    * nginx
    * apache
* WAS Framework
    * Spring
    * SpringBoot
    * Node-express
    * PHP
* Queuing
    * RabbitMQ
    * Kafka
* Security
    * OAuth
    * Basic Authentication
    * Token Authentication
    * JWT
    * OpenID
* Search Engine
    * Elasticsearch
    * Solr

### DevOps 기능
* Langualge
    * Python
    * Ruby
    * Node.js
    * Go
    * C/C++
* OS
    * Linux
* Networking
    * DNS
    * OSI Model
    * HTTP
    * HTTPS
    * FTP
    * SSL/TLS
* CI/CD
    * Jenkins
    * Travis CI
* Container
    * Docker
* Configuraztion Management
    * Ansible
* Container Orchestration
    * Kubernetes
* Infrastructure Provisioning
    * Teraform
* Monitoring
    * ELK
    * Graylog
* Cloud
    * AWS
    * GCP
    * AZURE

기본적으로 풀 스택 엔지니어는 위와같은 기술들에 대해서 이해하고 사용할 줄 알아야 한다고 생각합니다.
그러나 책에서 다룰 내용은 볼드 처리된 내용에 대해서만 집중적으로 다루어 볼 예정입니다. 
또한 어떤 내용은 간단하게 개념만 확인할 것입니다. (예) AWS, ELK 등

좀 더 디테일한 로드맵을 확인하고 싶다면 https://github.com/kamranahmedse/developer-roadmap 을 참조하시길 희망합니다. 
해당 사이트에 제시된 기술들을 더 깊이있게 공부해 보시면 좋을듯 합니다. 

## Wrap up
지금까지 웹이 변해왔던 과정을 간단하게 알아보았습니다. 
정적 페이지를 제공던 시기부터, JSP, PHP, ASP 와 같이 XX페이지 방식개발, 안정성과 유지보수성의 필요로 인해서 웹서버와, 웹어플리케이션 서버, 데이터베이스로 분리된 3티어 아키텍처로 발전도 살펴 보았습니다.
프런트엔드 기술중 AJAX 가 나타나면서, 획기적인 발전이 일어났고, 이를 계기로 웹 개발도 점점 고도화 되었고, 최근에는 프런트엔드 기술은 SPA 로 발전하였고, 서버사이드는 다양한 클라이언트를 수용하기 위해서 RESTful API 방식으로 진화된 과정도 알아보았습니다.

지금 IT에서는 MSA 가 대세가 되면서, 시스템은 복잡해지고, 알아야하는 기술은 더 많아지게 되었습니다.

지금과 같은 환경에서, 그리고 더욱 폭넓고 다양하게 변모할 상황에서 풀 스택 엔지니어가 된다는 것은 그야말로 개발자의 가치를 올리는 가장 좋은 방법이라 생각이 듭니다. 

우리는 풀스택 엔지니어가 되기 위해서 프런트엔드, 백엔드, DevOps 관점에서 어떠한 기술들이 있는지 알아보았고, 간략하게나마 어떤 기술들을 이 책에서 다룰 지에 대해서도 알아보았습니다. 

단순히 서버사이드 개발자라고 하거나, 프런트 엔드 전문가 로 머물러 있는것 보다, 시스템을 서비스 전체 관점에서 설계하고, 개발 할 수 있는 기술을 가지는 것은 매우 흥미로운 일이 아닐 수 없습니다. 
이제 본격적으로 그 여행을 떠나 보도록 하겠습니다.







1.2 Wrap Up

[목록으로](https://github.com/unclebae/letsBecomeFullStackEngineer)
