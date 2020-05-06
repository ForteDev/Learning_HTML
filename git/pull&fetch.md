# git pull과 git fetch의 차이점은?

*이 문서는 아래 링크의 영어 문서를 번역한 것입니다. 99%의 확률로 오역이 있을 수 있습니다.*  
<https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull>

Before we talk about the differences between these two commands, let's stress their similarities: both are used to **download** new data from a remote repository.
두 명령어의 차이점을 설명하기에 앞서 두 명령어의 공통점에 중점을 두어 생각해볼까? 두 명령어는 모두 원격 저장소에서 새로운 데이터를 **다운로드**한다는 공통점이 있어.  

Downloading data is an essential step in your daily work - because the remote data you are looking at in your local repository is just a "snapshot". It's only as up-to-date as the last time you **explicitly** downloaded fresh data from the remote with "fetch" or "pull". It's vital to keep this fact in mind when inspecting remote branches and commits!
새로운 데이터를 다운로드 하는 과정은 일상적인 작업에서 꼭 필요한 단계야. 왜냐면 로컬 저장소에 있는 원격 데이터는 일종의 스냅샷\*일 뿐이거든. 로컬 저장소의 파일은 `fetch`와 `pull`로 원격 저장소에서 신선한 데이터를 다운로드하면서 최근에 업데이트한 
Let's now look at the fine but important differences between "fetch" and "pull".