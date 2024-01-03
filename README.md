Uygulamanın IDE gerekmeden çalıştırılması için kurulumu:
1. Backend uygulamasının olduğu dizinde konsolu çalıştırın ve konsola 'mvn clean install' yazın ve çalıştırın.
2. Spring Boot projeniz için bir executable JAR dosyası oluşturulacak. Bu JAR, genellikle target/ klasöründe bulunur ve java -jar target/myapp-0.0.1-SNAPSHOT.jar komutu ile çalıştırılır.
3. Ardından React uygulamasının bulunduğu klasörde konsolu açın ve 'npm install' yazın ve çalıştırın.
4. 'npm run build' yazın ve çalıştırın.
5. Oluşan "build" dosyasının içeriğini backend uygulamasının src/main/resources/static dizinine yapıştırın.
6. Backend dizininde çalışan konsolda jar target/form-0.0.1-SNAPSHOT.jar komutu ile jar dosyasını çalıştırın.
7. React uygulamasının bulunduğu klasörde konsolu açın ve 'npx serve -s build' komutunu çalıştırın ve http://localhost:3000/ adresinden uygulamayı test edebilirsiniz.
