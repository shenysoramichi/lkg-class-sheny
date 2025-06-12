FROM openjdk:8-jdk-alpine

# 设置工作目录
WORKDIR /app

# 将打包好的 JAR 文件复制到镜像中
COPY app/BookManager-1.0.5.jar /app/app.jar

EXPOSE 8080

# 运行 JAR 文件
ENTRYPOINT ["java", "-jar", "/app/app.jar"]
