# Login Screen

## Detail

### Design

|  ลำดับ | หัวข้อภาษาไทย      | หัวข้อภาษาอังกฤษ  | คีย์เปลี่ยนภาษา | Data type | ตัวอย่างข้อมูล|
|-:|:-|:-|:-|:-:|:-|
|1|อีเมล / หมายเลขโทรศัทพ์|Email/Phone nember|login__username|String|0999999999|
|2|รหัสผ่าน|Password|login__password|String|123456|
|3|จำรหัสผ่าน|Remamber Password|login__remember_password|Boolean|true|

### API

* get_login

```JSON
{
       "username":"0999999999",
       "password":"123456",
}
```

* get_profile_data

```JSON
{
       "id":"",
       "firstname":"",
       "lastname":"",
       "birth_day":"",
       ....
}
```
