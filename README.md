<!-- KRitter90.github.io -->
<!-- DOCTYPE html -->
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title> This is the debugging testpage </title>
  </head>
  <body>
    <p>Here I will try to make my first log in form using html coding. </p>
    <section>
      <h2> Section 1 </h2>
      <ol>
        <li> learn different tags to get familiar with listing options </li>
        <li> coding an ordered list could be helpful</li>
        <li> be aware that an unordered list also exists </li>
      </ol>
    </section>
    <section>
      <h2> Section 2 </h2>
      <p> Here, I will also add a paragraph. So why am I doing all of this?
        There are so many ways to learn new things for free.
        I think that is super fun. Here I will break the line:
      <br> When breaking a line, no ending tag is needed. It works just like this. 
        So Let's say I want to write even more and make the reader put some extra focus on the next line. What will happen if I add a "hr"?
      <hr> The hr also does not require any ending tag. So what is the difference between "br" and "hr"? 
      So maybe, let's just end this paragraph for now.</p>
        <section>
          <h4> Subsection 2.1 </h4>
            <p> So this is how to write a nice looking subsection. No containers or pictures needed - it actually works with simple text formatting tips. I am very glad that I just found out and can now try more how to use them accurately. I guess less is sometimes more. </p> 
        </section>
        <section>
          <h4> Subsection 2.2 </h4>
            <p> Some more text in the next sub section. I could easily call this a Chapter... </p> 
        </section>    
    </section>
    <section> 
      <h2> Section 3: How to use different tags in html </h2>
      <p> I think here I will quickly use different tags to see how they look like once compiled. </p>
         <section> 
          <h4> Subsection 3.1 : How to use the tag: button </h4>
          <p> Now I will make a button </p>
          <button id="my_first_button" width="5px" height="3px" name="button_no_one" value="click">click me!
          </button>
          <p> Now I will make a second button! <br> Can I also make a button here? 
            <button id="my_second_button" width="6px" height="4px" name="button_no_two" value="click2">click me 2!
            </button></p>
          </section> 
      <!-- This section is about the meter-tag-->
          <section> 
            <h4> Subsection 3.2 : How to use the tag: meter </h4>
            <p> Now I will make a meter </p>
            <label for="my_first_meter">This is the label for the first meter</label>
            <meter id="my_first_meter" min="0" max="20" name="meter_no_one" value="4">This is 4 out of 20 </meter><br>
            <p> Now I will make a second meter with more lines in it! <br> Can I also make a meter after the end of this paragraph?</p>
            <label for="my_second_meter">This is the label for the second meter</label>
            <meter id="my_second_meter" min="0" max="20" name="meter_no_two" value="12">This is 12 out of 20 </meter>
            and directly one more
            <meter id="my_third_meter" min="0" max="20" name="meter_no_three" value="8">This is 8 out of 20 </meter> <br>
            <meter min="0" max="20" value="13">This is 13 out of 20 </meter> 
            <meter min="0" max="20" value="7">This is 7 out of 20 </meter> <hr>
            Alright so let's say I want to show the current process of my self-written homepage. For this, I would like to add progress instead of meter. <br>
            So let's go to the next subsection
          </section>
          <!-- This section is about the progress-tag-->
          <section> 
            <h4> Subsection 3.3 : How to use the tag: progress </h4>
            <p> So here is now the overview if my current progress of the self-written webpage </p>
              <label for="progress1">Added all pages.</label>
              <progress id="progress1" value="84" max="100"> 84% </progress> <br>
              <label for="progress2">Made a user log-in form.</label>
              <progress id="progress2" value="0" max="100"> 0% </progress> <br>
              <label for="progress3">Coding in html5.</label>
              <progress id="progress3" value="98" max="100"> 98% </progress> <br><hr>
          </section> 
   </section>
   <section>
     <h2> The final step to make users sign-in or register </h2>
     <p> Alright. So here is now the few steps on how to build the log-in form how I want it to be on the web-page. <br></p>
     <h3> Step 1: Sign-in form </h3>
     <!-- add here the form -->
      <form action="/action_page.php" method="get">
        <label for="fname">First name:</label>
        <input type="text" id="fname" name="fname"><br><br>
        <label for="lname">Last name:</label>
        <input type="text" id="lname" name="lname"><br><br>
        <label for="pw">Password:</label>
        <input type="password" id="pw" name="pw"><br><br>
        <input type="submit" value="Submit"><br>
        Not a member yet?
        <button id="button_form" width="20" height="12" name="button_form">register</button><br>
        (C) 2020 Ritter90. 
      </form> 
   </section>
 </body>
 <hr>
  
  <aside>
    <p>Where does the aside paragraph end up at?</p>
  </aside>
  
  <footer>  <hr> This is my footer. Will it be at the end of the webpage?
    <nav>
      <p> How about I add a navigation part inside my footer? </p>
    </nav>
  </footer>
  
</html>
