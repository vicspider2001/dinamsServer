return all roomtypes
http://localhost:1800/rooms

return roomtypes wrt floor
http://localhost:1800/floor=1


return roomtypes wrt roomType_Id
http://localhost:1800/details=1


return all checkinRooms
http://localhost:1800/checkin


return checkinRooms wrt roomnums
http://localhost:1800/checkin?guest=305

return all checkoutRooms
http://localhost:1800/checkout


return checkoutRooms wrt guestDetails
http://localhost:1800/chkoutguest


Check a guest into check in Database
http://localhost:1800/bookNow


post Bill of a guest in Check in Database
http://localhost:1800/bill


Check a guest out from checkin database into checkout database
http://localhost:1800/checkout
http://localhost:1800/delBooking


Update Guest details
http://localhost:1800/guestupdate/:id


Room Change
http://localhost:1800/guestupdate/:id

return all local reservations
http://localhost:1800/reserve

return all website reservations
http://localhost:1800/ebooking

make a local reservations
http://localhost:1800/reserveNow

update room status
http://localhost:1800/rmstatus/:id


get room status
http://localhost:1800/getrmstatus

get organisations database
http://localhost:1800/org

get organisations wrt company
http://localhost:1800/org?group=1
