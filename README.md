# buildgradle
plugins {
    id 'java-library'
}
repositories {
    mavenCentral()
}

dependencies {
    testImplementation (
            "com.codeborne:selenide:5.20.3",
            "org.junit.jupiter:junit-jupiter-api:5.7.1")
    testRuntimeOnly "org.junit.jupiter:junit-jupiter-engine:5.7.1"
}
test {
    useJUnitPlatform()
}
![image](https://user-images.githubusercontent.com/53948043/140180530-2e3e887e-a7e0-46ee-9e4c-ef3fe2c8c796.png)
