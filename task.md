# Task Details

Consider there is a teacher who wants to teach students online. The teacher has specified their availability for the weekdays. You will be given the availability for a teacher in a JSON format.

The teacher now wants to accept requests for a class from the students. In response to each request the teacher wants to reply with a date and the time slot for which the class is scheduled. Your task is to give the students a way to book classes. That can be divided into the following sub-tasks:

1. Create a `Django`/`Express.JS` application for this task

2. Read the `teacher_availability.json` file given to you in memory.

3. Create an API Endpoint on which the student can send a `POST` Request containing their full name and their preferences for taking the class.

4. The request will contain the student's name, email address and their prefered day and time slot.

5. If a teacher is available at the student's preferred day and time slot, store the same in your application and send the confirmed date and time slot back in response.

6. Additionally, send an email to the student with the confirmed date and time slot details for the class. (You do not need to actually send the email, just write the available function in your chosen framework that sends email including the Student's Name, Class Date, Class Start Time and End Time in its body.)

7.  If a teacher is booked for a student’s preferred weekday, check for the same day, next week and repeat this procedure unless you find a date on which the teacher is available.

8.  Keep updating the teacher availability for the days on which slots are booked.

9.  Sample JSON for teacher availability, student request format and response format can be found [here](./README.md)
