# MyGram

`MyGram adalah aplikasi yang dapat digunakan menyimpan foto maupun membuat comment untuk foto orang lain. Aplikasi ini dibangun menggunakan bahasa pemrograman Go dan menggunakan framework gin-gonic.`

## Prerequest
Berikut beberapa library yang digunakan:
- go get github.com/asaskevich/govalidator
- go get github.com/dgrijalva/jwt-go
- go get github.com/gin-gonic/gin
- go get golang.org/×/crypto
- go get gorm.io/driver/postgres
- go get gorm.io/gorm
Berikut tools yang digunakan:
- Database Postgres
- Framework Gin Gonic
- Gorm untuk koneksi database

MyGram memiliki 4 Table yaitu:
![image](https://github.com/RinaldiPakpahan/MyGram/assets/26915668/3f3f8401-a94a-4ed8-92bd-b1cd09623645)

Untuk endpoint yang digunakan adalah sebagai berikut:
1. User:
   - Register [POST]
   - -Login [POST]
2. Photo :
   - GetAll [GET]
   - GetOne [GET]
   - CreatePhoto [POST]
   - UpdatePhoto [PUT]
   - DeletePhoto [DELETE]
3. Comment :
   - GetAll [GET]
   - GetOne [GET]
   - CreateComment [POST]
   - UpdateComment [PUT]
   - DeleteComment [DELETE]
4. Social Media :
   - GetAll [GET]
   - GetOne [GET]
   - CreateSocialMedia [POST]
   - UpdateSocialMedia [PUT]
   - DeleteSocialMedia [DELETE]

Dengan endpoint diatas maka kita dapat melakukan request register dan login User melalui API dan create, update, dan delete juga melalui API MyGram

Berikut link postman collection MyGram:
https://github.com/RinaldiPakpahan/MyGram/blob/main/MyGram.postman_collection.json


