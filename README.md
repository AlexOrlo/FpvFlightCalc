

Main purpose of this project is to help for FPV pilots, who
used PitLab Auto Pilot to calculate main flight parameters before flight.

How we know (users of PitLab), we can save beautiful log
from ground station with all flight parameters.

In this project I try according to this log to calculate “flight
model” of your plan and give you instrument to simulate flight with calculated
model.

Main parameters in flight model is Battery voltage (20
points of voltage on function of Ah) and internal resistance, cruise power,
cruise speed, climb and drag parameters, turn speed and so on.

In the project also consider wind, itch have two models of
calculation: simple single wind for all heights and area and more detail model,
that calculate gradient of wind by height and area.

Flight calculated by PID controllers.

I try to repeat main logic of PitLab AP: flight to wp, flight
on rout, landing on ran way.

In the final of calculation, you can to know of parameters on the whole path. 

In this project used very powerful GIS engine: ArcGIS for Java,
that have free license for non-commercial programs.

So, this project written on Java.

Main JAR named FPV.

Also added rar archives, which you need to unpack to the main folder.

Additional jar’s is library of java ArcGIS
engine.

Also you can found folder “legal”, with
ArcGIS licenses for free projects.

For now, I try to record video on YouTube
with more detail instructions. 

