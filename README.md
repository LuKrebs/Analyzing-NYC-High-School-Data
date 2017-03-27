<p><a href="https://en.wikipedia.org/wiki/SAT">SAT</a> or Scholastic Aptitude Test, is a test given to graduating high schoolers in the US every year. The SAT has 3 sections, each of which is worth a maximum of 800 points. The SAT is used by colleges to determine which students to admit. High average SAT scores are usually indicative of a good school.</p>

<p>New York City has published data on the <a href="https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4">SAT scores of students</a>, along with additional demographic datasets. We combined the following datasets into a single, clean, Pandas Dataframe:</p>

<ul>
  <li><a href="https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4">SAT scores by school</a> - SAT scores for each high school in New York City.</li>
  <li><a href="https://data.cityofnewyork.us/Education/School-Attendance-and-Enrollment-Statistics-by-Dis/7z8d-msnt">School attendance</a> - attendance information on every school in NYC.</li>
  <li><a href="https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3">Class size</a> - class size information for each school in NYC.</li>
  <li><a href="https://data.cityofnewyork.us/Education/AP-College-Board-2010-School-Level-Results/itfs-ms3e">AP test results</a> - Advanced Placement exam results for each high school. Passing AP exams can get you college credit in the US.</li>
  <li><a href="https://data.cityofnewyork.us/Education/Graduation-Outcomes-Classes-Of-2005-2010-School-Le/vh2h-md7a">Graduation outcomes</a> -  percentage of students who graduated, and other outcome information.</li>
  <li><a href="https://data.cityofnewyork.us/Education/School-Demographics-and-Accountability-Snapshot-20/ihfw-zy9j">Demographics</a> - demographic information for each school.</li>
  <li><a href="https://data.cityofnewyork.us/Education/NYC-School-Survey-2011/mnz3-dyi8">School survey</a> - surveys of parents, teachers, and students at each school.</li>
</ul>

<p>New York City has a significant immigrant population, and is very diverse, so comparing demographic factors such as race, income, and gender with SAT scores is a good way to figure out if the SAT is a fair test. If certain racial groups consistently performed better on the SAT, we would have some evidence that the SAT is unfair, for example.</p>
