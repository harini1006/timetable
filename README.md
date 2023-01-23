# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag

### STEP 2
Add header row using th tag

### STEP 3
Add your timetable

### STEP 4
Execute the program


# CODE
```
<!DOCTYPE html>
<html>
<center>
   <head>
    <title>🗓️TIME TABLE🗓️</title>
    <link rel="icon" href="https://media.discordapp.net/attachments/533340656987275284/906080541344956436/kissclipart-saveetha-university-chennai-logo-clipart-saveetha-3a90c06681798db2.png" type="image/icon type">
  </head>
   <body>
      <table border = "1" cellspacing="1" bordercolor="#C19A6B" bgcolor="transparent">
         <tr>
            <th colspan="8">TIME TABLE</th>
            <br></br>
	 <table border = "1" cellspacing="1" bordercolor="#C19A6B" bgcolor="transparent">
    <br></br>
<img src="/static/images/logo.png" width="662" height="100">
 <tr>
 <th colspan="10">TIME TABLE</th>
 </tr>
 <tr>
  <br></br>
<th colspan="5">Name:           Harini V. </th> <!--Enter Your Name Here-->
<th colspan="5">Reference Number:        22004214 </th> <!--Enter Your Reference Number Here-->
         </tr>
         
         <tr>
            <th>DAYS</th>
            <th>8:00-9:00</th>
            <th>9:00-10:00</th>
            <th>10:00-11:00</th>
            <th>11:00-12:00</th>
            <th>12:00-1:00</th>
            <th>1:00-2:00</th>
            <th>2:00-3:00</th>
            <th>3:00-4:00</th>
            <th>4:00-5:00</th>
         </tr>

<!--Note-->
<!--Make Changes If Time Table Varies-->
<!--And also fill the empty spaces if you got the class on the area or vice versa-->
<!--and hey dont forget to change it below too at the line "85 to 92" -->

          <tr>
             <td align="center">MONDAY</td>
             <td align="center">---</td>
             <td align="center">---</td>
             <td align="center">19AI414/Obed Otto C</td>
             <td align="center">19AI414/Obed Otto C</td>
             <td align="center">L</td>
             <td align="center">19EN614/Anandkumar K</td>
             <td align="center">19EN614/Anandkumar K</td>
             <td align="center">19MA211/Anandan V</td>
             <td align="center">---</td>
             
         </tr>
	 <tr>
             <td align="center">TUESDAY</td>
             <td align="center">19EY701/Saranya V</td>
             <td align="center">19EY701/Saranya V</td>
             <td align="center">---</td>
             <td align="center">---</td>
             <td align="center">U</td>
             <td align="center">19AI414/Obed Otto C</td>
             <td align="center">19AI414/Obed Otto C</td>
             <td align="center">---</td>
             <td align="center">---</td>
         </tr>
	 <tr>
             <td align="center">WEDESDAY</td>
             <td align="center">---</td>
             <td align="center">---</td>
             <td align="center">19EN101/Sunitha Deva Kumari D</td>
             <td align="center">19EN101/Sunitha Deva Kumari D</td>
             <td align="center">N</td>
             <td align="center">19AI414/Obed Otto C</td>
             <td align="center">19AI414/Obed Otto C</td>
             <td align="center">19CY205/Shanthi S</td>
             <td align="center">19CY205/Shanthi S</td>
         </tr>
	 <tr>
             <td align="center">THURSDAY</td>
             <td align="center">19MA211/Anandan V</td>
             <td align="center">19MA211/Anandan V</td>
             <td align="center">19CY205/Shanthi S</td>
             <td align="center">19CY205/Shanthi S</td>
             <td align="center">C</td>
             <td align="center">---</td>
             <td align="center">---</td>
             <td align="center">19AI304/Magitha</td>
             <td align="center">19AI304/Magitha</td>
         </tr>
  	 <tr>
             <td align="center">FRIDAY</td>
             <td align="center">19EN614/Anandkumar K</td>
             <td align="center">19EN614/Anandkumar K</td>
             <td align="center">19MA211/Anandan V</td>
             <td align="center">19MA211/Anandan V</td>
             <td align="center">H</td>
             <td align="center">19AI304/Magitha</td>
             <td align="center">19AI304/Magitha</td>
             <td align="center">19EN101/Sunitha Deva Kumari D</td>
             <td align="center">19EN101/Sunitha Deva Kumari D</td>
         </tr>
         
      </table>
      <h2><u>Enrolled Subject</u></h2>
<H3>1. 19AI414 - Fundamentals of Web Application Development </H3>
<H3>2. 19EN614 - Japanese Basic</H3>
<H3>3. 19MA211 - Statistics and Numerical methods</H3>
<H3>4. 19EN101 - Communicative English</H3>
<H3>5. 19CY205 - Principles of Chemistry in Engineering</H3>
<H3>6. 19AI304 - Fundamentals of C Programming</H3>
<H3>7. 19EY701 - Soft skills</H3>
</body>
<style>
    body {
      background: linear-gradient(to right, #ADD8EF, #FFB6C1);
      color: #333333;
      font-family: "Euclid Circular B Medium", Poppins;
    }
     <script>
    .footer {
      padding: 32px 0;
      position: absolute;
      width: 100%;
      background-color: red;
      color: white;
      text-align: center;
      background: rgba(255, 255, 255, 0.5);
      box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
      backdrop-filter: blur(9px);
      -webkit-backdrop-filter: blur(9px);
      border: 1px solid rgba(255, 255, 255, 0.18);
    }
    .footer p {
      margin: 0;
      line-height: 26px;
      font-size: 15px;
      color: #990099;
    }
    .footer p a {
      background: linear-gradient(to right, #f27121, #e94057, #8a2387);
      color: transparent;
      -webkit-background-clip: text;
      background-clip: text;
      text-decoration: none;
    }
    .footer p a:hover {
      color: white;
    }
  </style>
        
</html>
```

# OUTPUT
![output](/OUTPUT.png)

# HTML VALIDATOR
![HTML VALIDATOR](/VALID.png)

# RESULT
The program for creating time table is  completed successfully 