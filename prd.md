SOFTWARE ENGINEERING
GROUP B, BU COS 209
GROUP 6
BABCOCK RIDE (BU-KEKS)
1. Product Overview

The product is Babcock Ride. It is a campus web application that connects Babcock University students with tricycle (Keke) drivers on campus so students can easily see available Kekes and book rides, while drivers can see where students are waiting.

2. Problem Statement

Students are heavily reliant on tricycles (Kekes) to get around campus each day. However, there is a limited number of Kekes on campus and no proper way to coordinate where they go. Because of this, students face delays in getting rides, while drivers waste time and fuel driving around empty in areas where nobody is waiting.

From what we observed and heard on campus, getting a Keke is especially difficult when students are rushing for 7:00 AM classes and when traveling long distances within the campus. Drivers also have no way of knowing in advance how many students are waiting together, where the students are, or whether a student is willing to pay for all the seats so the Keke can depart immediately.

3. Our Campus Research and Interviews

To understand how this affects both sides daily, our group observed campus transportation and interviewed 17 students (freshers and returning students) and 6 Keke drivers.

What Students Currently Do
Struggle to get Kekes for 7:00 AM classes: Most students we spoke with said getting a Keke on time for 7:00 AM classes is a real challenge, as they are forced to leave their hostels early and simply hope an empty Keke passes by.
Walk around and wait at junctions: Students walk from one spot to another looking for Kekes or stand at busy points while already full Kekes pass by, particularly when they are traveling long distances across campus.
Ask other students where to find Kekes: Freshers especially do not know the usual spots where Kekes pass or park, so they have to ask older students where to catch one.
Group ride mismatches: When a group of 4 or 5 friends is going to class together, a smaller 3-seater Keke may stop for them but has to turn them down because it can only take 3 passengers.
What Keke Drivers Currently Do
Roam without knowing where students are: Drivers move around guessing where passengers are waiting, wasting fuel and time, particularly before the 7:00 AM lectures.
Avoid certain routes or get stuck with mismatched group sizes: Drivers do not know in advance where students are going or how many students are waiting together.
Wait around to fill empty seats: Drivers often delay departure until all 3 or 5 seats are filled, even when a student is in a hurry, while some students are willing to pay for the remaining seats so they can leave immediately.
4. Objectives
Connect students and Keke drivers directly so students can book rides on time, especially for 7:00 AM classes and long distances within campus, while drivers know where they should be.
Match students with the appropriate Keke capacity (3-seater vs. 5-seater) so drivers know the exact passenger count before arriving.
Give students the option to pay for all 3 or 5 seats when both parties agree, allowing the driver to depart immediately without waiting for additional passengers.
5. Proposed Solution (Babcock Ride)

We propose Babcock Ride, a straightforward campus web application that connects students and Keke drivers without requiring complex live GPS tracking in the first version:

Pick campus locations, group size, and Keke type: A student selects a campus pickup point, chooses their destination, selects how many students are riding (1 to 5), and indicates whether they need a 3-seater or a 5-seater Keke, or whether they wish to pay for all 3 or all 5 seats for a quicker direct trip.

See nearby Kekes and driver willingness: The app uses predefined campus zones and distances between landmarks so students can see which Kekes are nearby. Drivers can see the destination, passenger count, and full-Keke payment option before accepting a request.

Accept and meet: A driver with the appropriate seat capacity accepts the request if both sides agree. The driver either goes to the pickup point or the student meets the driver there so the trip can begin immediately.

6. First Version (MVP) Features

Version 1 focuses strictly on solving the core problem cleanly before choosing any programming language or framework:

Student and Driver Login: Separate accounts for students and verified campus Keke drivers, registered as either 3-seater or 5-seater Keke operators.
Campus Stops and Distance Zones: A predefined list of campus pickup and drop-off points (SAT, BUSA, BBS, hostels, gates) with simple zone distance indicators so students know how close a Keke is.
Seat Count and Full-Keke Option: Allows drivers to see exact passenger counts beforehand (e.g., 5 students going to class) and lets a student choose to pay for all 3 or 5 seats, if both parties agree, so the driver can depart immediately.
Timely Ride Requests: Allows students to book rides on time, especially for 7:00 AM classes and long distances within campus, and enables drivers to see destinations and accept trips they are willing to take.
Simple Ride Status: Displays Requested, Accepted, or Completed so both students and drivers know when and where to meet.

Out of Scope for Version 1: In-app wallet or card payments (cash or bank transfers remain the payment methods), live turn-by-turn map navigation, and app store downloads (the system runs in a phone browser).