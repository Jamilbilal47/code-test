# Thoughts

This code has some good practices like I can see in the BookingRepository lazzy loading has been used which is a good part of it. but it is a kind of complex code at some points due to its structure means how its database desigend. like its calling relation of relations at multiple places. at some points code is very lengthy like in function I never recommond or follow the lenghty function practices. I mark as a average code this one because I do not perfer these lengthy functions and repetitive functionality again and again.


# Optimization
there are some points which we can optimize:
 - we can use some laravel buildin method like for authentication we can use Auth function like check etc instead of request in BookinController index funtion and all the other places where that has been used. and in the same line we should config files instead of env. env file should only contain server or application env related things. but this is related to admin roles so it should be store in the database where we can get all the roles.
 - there are many function we are not understandable until then we can't fint its description or well commented like show function.
 - for store method there should be some common helper method for the statues and we can store the directoly by using sync methods.
 - I also found some naming convention issues like cname is a variable name which has no sense to me that what it is.
 - I do not find any kind of validation while storing the data in database.
 - not using any fillable property that should be there is case of firing events etc.
 - Inshort this can be really doable thing in a very easyway. somewhere code is very complex and lengthy too many conidtions to get understand it should be very clean code.



I have mentioned some points which nned to be improve in my thought. I couldn't get through the complete bookingrepository file because it is too lengthy.



