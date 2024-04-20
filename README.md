<h1># Ticket-booking-System</h1>
The Java-based IRCTC Ticket Booking System is a software application, Inspired by the Indian Railway Catering and Tourism Corporation (IRCTC) platform, mainly build BackEnd Working of the application using JAVA.
<hr><br>
<h2>#Features:</h2>
1. able to Login and SignUp.<br>
2. Fetch/Search trains A --> B.<br>
3. Show available seats.<br>
4. Book Seat.<br>
5. Ticket Fetch.<br>
<hr>
<h2>LOW LEVEL DESIGN(LLD) Entites and Service:</h2>
<hr>
<h2>Entities:</h2>
<h3>USER:</h3>
1. String name<br>
2. String hashedPassword<br>
3. String List<Ticket> ticketBooking<br>
4. String UserId<br>
<h3>TICKET:</h3>
1. String ticketsId<br>
2. String UserId<br>
3. String Source<br>
4. String destination<br>
5. String DataTime dateOfTravel<br>
6. String Train train<br>
<h3>TRAIN:</h3>
1. String trainId<br>
2. String trainNo.<br>
3. StringDataTime departureTime<br>
4. String DataTime arrivalTime<br>
5. List<List<Boolean>> Seats<br>
6. Map<String, Date> starting<br>
<hr>
<h2>SERVICES:</h2>
<h3>USERBOOKING:</h3>
1. LoginUser(User user)<br>
2. SignUp(User user)<br>
3. FetchBooking(User user)<br>
4. Cancle(___)<br>
5. BookTicket(String A, String B)<br>
<h3>TRAIN SERVICE:</h3>
1. SearchTrain(String A, String B); A --> B <br>
2. GetSeatsAvailable(Train t1)
<hr>
