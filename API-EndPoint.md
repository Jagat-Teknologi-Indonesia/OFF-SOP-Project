
# Standarisasi API EndPoint

### Module Authentication
**/auth/signup**
_Untuk signup buatan sendiri (by email/hp)_
**/auth/signup/3rd/**
_Hit disini akan menampilkan pilihan 3rd Party SignUp yang tersedia_
**/auth/signup/3rd/facebook**
**/auth/signup/3rd/google**
**/auth/signup/3rd/github**
**/auth/signup/3rd/twitter**

**/auth/login**
_Untuk login langsung dengan buatan sendiri (by email/hp)_
**/auth/login/3rd/facebook**
**/auth/login/3rd/google**
**/auth/login/3rd/github**
**/auth/login/3rd/twitter**

**/auth/reset/**
_Untuk reset password dari halaman Login Awal (Sebelum Login)_

### Module Account

**/user/{id}/profile/**
_Untuk Admin/Manage (Logedin), melihat profile orang lain_
**/user/se/profile/**
_Untuk self user sendiri (Logedin), {id} diganti **se**_
**/user/{id}/profile/edit**
**/user/{id}/email/change**
**/user/{id}/password/change**
_Untuk ganti password dari halaman profile (Logedin)_

### Module Relation

**/rel/follow/add/{id}**
_Untuk menambah follow ke orang lain (Logedin)_
**/rel/follow/del/{id}**
**/rel/follow/get/{id}**   **/rel/follow/list/{id}**
_Untuk melihat list follower_
**/rel/subscribe/add/{id}**
**/rel/subscribe/del/{id}**
**/rel/subscribe/get/{id}**
