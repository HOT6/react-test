# docker image update
  1. travis-ci를 통해 jar 파일 생성 및 도커 이미지 eks 업로드 진행 (`.travis.yml`)
  2. kubenetes deployments 재시작
  ```
  kubectl rollout restart deployment spring-boot-demo
  ```


# usage
```
cd demo-react
npm i
npm run build

cd ../demo
mvn clean install

java -jar demo/target/demo-*.jar
```
