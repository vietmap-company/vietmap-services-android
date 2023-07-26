# vietmap-services-directions
vietmap-services-android

License by Vietmap company.
# vietmap-java-services-for-android-navigation-sdk

build release: 

./gradlew :services:assemble


tạo thư mục mới, copy file services.jar vào
tại terminal, cd tới thư mục tạm và chạy lệnh sau:

jar xf services.jar 

 Mở thư mục com/mapbox/api/direction/v5 và xoá file có tên
# AutoValueGson_DirectionsAdapterFactory 
quay lại terminal, chạy lại lệnh

jar cf services.jar .

copy file jar mới tạo và đẩy v repo sau 

https://github.com/vietmap-company/vietmap-services-android