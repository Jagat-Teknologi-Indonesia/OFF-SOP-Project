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
**/user/profile/**
**/user/profile/edit**
**/user/email/change**
**/user/password/change**
_Untuk ganti password dari halaman profile (Logedin)_

**/user/<id>/email/change**

### Module Relation
**/rel/follow/**
**/rel/subscribe/**
