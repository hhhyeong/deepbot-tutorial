
# 딥러닝 음성챗봇
---
## 강의 시작전 확인해 주세요.

### Git 설치 및 공부하기

[Git - 간편안내서](https://rogerdudler.github.io/git-guide/index.ko.html)


### Heroku 계정생성

[Heroku 계정생성](https://www.heroku.com/)
[Heroku 설치](https://devcenter.heroku.com/articles/heroku-cli)

### 딥러닝 기초학습

[머신러닝 딥러닝 단기집중과정](https://developers.google.com/machine-learning/crash-course/?hl=ko)

### Konlpy 설치

[Konlpy 설치](http://konlpy.org/)

- Konlpy 설치시 이슈사항 체크

### NLTK 설치 이휴

- [Mac OSX에서 NLTK Data 설치하기](http://corazzon.github.io/nltk_data_install)

### Python virtualenv

- [Python virtualenv(Linux/Windows)](https://dgkim5360.tistory.com/entry/python-virtualenv-on-linux-ubuntu-and-windows)


### Colab 사용하기

- [CoLab 가이드](https://zzsza.github.io/data/2018/08/30/google-colab/)
---

## 1일차 - 음성챗봇 프레임워크

- 음성챗봇 프레임워크 시연
- 음성챗봇 프레임워크 구조설명
- 프런트앤드 코드설명 (STT, TTS)
- 백앤드 코드설명 (Flask, JWT)
  * [flask-jwt-auth](https://github.com/oleg-agapov/flask-jwt-auth)
- 커스터마이징
- Deploy to Heroku
  * [Custom Domain 설정 1](https://devcenter.heroku.com/articles/custom-domains)
  * [Custom Domain 설정 2](https://medium.com/@ethanryan/setting-up-a-custom-domain-for-your-heroku-hosted-app-6c011e75aa3d)


### Deploy to heroku

```
#!/bin/zsh

git add .
git commit -a -m "."
git push heroku master
```
